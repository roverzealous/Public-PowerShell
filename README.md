A collection of Modules and Scripts we use in PowerShell

**Start-Sync Module**

*This module will what ever folders you set. We use this to edit our PowerShell Profiles and then sync them across all profile locations.*

    Function Start-Sync {
        robocopy C:\FolderToCopyFrom\ C:\FolderToCopyTo\ /E /MIR
    }
