# Set-ScheduledScriptGmsaAccount
Change account to Group Managed Service Account for scheduled task


Command to use script :

```
Set-ScheduledscriptGmsaAccount -gMSAname 'gMSA_Account_Name' -Taskname 'Name_of_task' -TaskPath 'Path_of_task'
```

The parameter -TaskPath is optionnal, by default if it's empty, the path will be '\\'
