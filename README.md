# bash-scripting-assignment
bash_assignment
Overview
This repository contains a collection of Bash scripts designed to solve specific tasks, as outlined in the assignment. Each script is written with clear comments and follows best practices for Bash scripting.

Directory Structure
The repository is organized as follows: bash_assignment/ ├── create_directory_structure.sh ├── file_backup.sh ├── user_information.sh ├── disk_usage_alert.sh ├── file_permission_checker.sh ├── automated_backup.sh ├── process_monitor.sh ├── text_file_analysis.sh ├── system_information_report.sh └── simple_calculator.sh

1. create_directory_structure.sh
Description: Creates a specific directory structure in the /home/user/ directory. Usage: Run the script to create directories such as projects, documents, and downloads.

2. file_backup.sh
Description: Backs up all .txt files in a specified directory to a backup directory with a timestamp. Usage: ./file_backup.sh /path/to/directory

3. user_information.sh
Description: Displays user-related information such as username, user ID, group ID, home directory, and shell. Usage: ./user_information.sh

4. disk_usage_alert.sh
Description: Checks the root filesystem’s disk usage and sends an email alert if usage exceeds 80%. Usage: ./disk_usage_alert.sh

5. file_permission_checker.sh
Description: Checks and reports the read, write, and execute permissions of a specified file. Usage: ./file_permission_checker.sh /path/to/file

6. automated_backup.sh
Description: Compresses the /home/user/documents directory into a tarball and moves it to a backup directory. Scheduled to run daily via cron. Usage: ./automated_backup.sh

7. process_monitor.sh
Description: Monitors a specified process (e.g., apache2) and starts it if it’s not running. Logs actions to a file. Usage: ./process_monitor.sh

8. text_file_analysis.sh
Description: Analyzes a text file and reports the number of lines, words, and characters. Usage: ./text_file_analysis.sh /path/to/textfile.txt

9. system_information_report.sh
Description: Generates a system information report, including uptime, memory usage, CPU load, disk usage, and running processes. Usage: ./system_information_report.sh

10. simple_calculator.sh
Description: A simple calculator that performs basic arithmetic operations. Usage: ./simple_calculator.sh
