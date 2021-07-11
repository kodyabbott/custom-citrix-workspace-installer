# custom-citrix-workspace-installer
This script was originally created by Citrix to install Citrix Workspace.

Orignal Script credit to Dennis Span:

https://dennisspan.com/citrix-workspace-app-unattended-installation-with-powershell/

Modified a section of the PowerShell script (script.ps1) from the original script to import registry key to allow for certain USB devices as we could not do it via GPO for endpoints - Kody Abbott

Added a bat file to run PS script as admin automatically.

Credit to Matt for run as admin bat file:

https://stackoverflow.com/questions/7044985/how-can-i-auto-elevate-my-batch-file-so-that-it-requests-from-uac-administrator/12264592#12264592
