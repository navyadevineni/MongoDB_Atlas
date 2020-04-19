# MongoDB Atlas Backup
In this repo, I'm going to explain about the backup plan. While deploying in production, one should have backup plan without losing data.

MongoDB Atlas provides two methods for backups:

- <b>Continuous Backups</b> :  Within 24 hours, Atlas continuous backups allows one to restore from stored snapshots or selected point. You can also perform query operations.

- <b>Cloud Provider Snapshots</b> : Using the native snapshot functionality, it provides localized backup storage.

#### Automation

It enables you to configure and maintain MongoDB nodes and clusters.

![](https://docs.cloudmanager.mongodb.com/_images/how-it-works.png)
#### Monitoring 
It monitors real-time reporting, visualization, and alerting on key database and hardware indicators.

#### How to manage backups ?
1. <i>Edit a Backup’s Settings</i>

       Modify a backup’s schedule, storage engines, and namespaces filter.

2. <i>Stop, Restart, or Terminate a Backup</i>

       Stop, restart, or terminate a deployment’s backups.

3. <i>View a Backup’s Snapshots</i>

       View a deployment’s available snapshots.

4. <i>Delete a Snapshot</i>

       Manually remove unneeded stored snapshots from Cloud Manager.

5. <i>Resync a Backup</i>

        If your Backup oplog has fallen too far behind your deployment to catch up, you must resync the backup.

6. <i>Disable the Backup Service</i>

       Disable Cloud Manager Backup.

### MongoDB Cloud Manager

It is a hosted  backup, monitoring, and automation service and supports backing up and restoring MongoDB deployments from a GUI.
It creates your snapshot data at set of intervals.


