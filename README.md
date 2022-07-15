# WinStartup
Windows boot cleanup script

# Development Opens

- Run on boot, and once daily

- (init) proof of operations; write to log file with timestamp

- capture reference for batch files

# Tasks

- File Explorer Sidebar.Quick Links.Google Drive(G:)

- My Documents\ANYCUBIC, SOLIDWORKSComposer, LabVIEW Data, Custom Office Templates, Scanned Documents, Fax, KiCad, ...

- Right-click context

# Task Operations
Run on boot, and once daily

## Run on Boot

- Use Task Scheduler, 'Create Task...' [1]

- Add a new 'Action', to 'Start a program' running your selected batch file or EXE

- @note  you can use the Startup folder as an alternative; I feel seperating the task operation & config from the filesystem is cleaner

## Run Periodically

- Use Task Scheduler, 'Create Task...' [2]

- Create a new Trigger, Daily to Start at selected time

# References

1. https://www.howtogeek.com/138159/how-to-enable-programs-and-custom-scripts-to-run-at-boot/

2. https://www.makeuseof.com/tag/how-to-automate-windows-programs-on-a-schedule/