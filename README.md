# C1_migration
This project requires external files I will not include in the repo, please see instructions below.
You need to include all these files in the SAME folder/directory in order for this script to work.
Requires Cloud One deployment script (Windows script ONLY).
Requires the SCUT tool (SCUT.exe & SCUT.exe.config) to remove Apex One.
Requires admin privileges.
This script will force a restart on the machine if the SCUT.exe tool executes successfully.
This script will automatically determine if Apex One is present and if it's not it will install Cloud One. If Cloud one is already installed it will stop. This script is designed to be placed in a startup script or task scheduler on Windows but can also just be executed manually.
WORKFLOW: Run script once, removes apex and restarts. Run script again after restart and it will install Cloud One. You can't break anything with this because it's already programmed to handle any situation on its own.
