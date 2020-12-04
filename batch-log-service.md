### This application will be desinged to make troubleshooting batch issues and engage the concerned team easy in case of any issues.

Current process:
Batch jobs are scheduled in autosys and in case of any failures, support team will be notified with INC.
Support team will have to go through multiple steps as described below:
  1. Raise pre-approved production access for batch servers [issue: Resources are required have access to all batch servers]
  2. Identify the script location in Autosys and analyze the script to identify the log configurations [issue: Resources are required to have access to autosys and team specific job roles]
  3. Check for errors in log and notify/engage the application owner [issue: Difficulties in identifying the owner if not documented]

Disadvantages with this process,
  1. Lot of time and efforts are spent
  2. Requires extensive documentation and KT whenever new resource is onboarded.
  3. There is risk of un-intentional operations [i.e., script deletion, content modification etc...] since resources are granted server access.

---
Proposed:
Design a User Interface with below abilities:
  1. Search the job and download the required log.
  2. One click notify option to trigger a notification to application owner with error logs.

Advantages with this application,
  1. Access to servers, autosys and team specific job roles are not required.
  2. No need of application ownership documentation.
  3. Application specific knowledge is not required and hence dependency is eleminated.
