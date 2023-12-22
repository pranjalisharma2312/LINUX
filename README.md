# LINUX

# internsctl - Custom Linux Command

## Overview

internsctl is a custom Linux command implemented as a Bash script. It provides various functionalities to retrieve system information and perform user and file-related operations.

## Prerequisites

- Git Bash installed on your system

## Usage

1. *Clone the Repository:*
   git clone <repository_url>
   

2. *Navigate to the Repository:*
   cd <repository_folder>
   

3. *Make the Script Executable:*
   chmod +x internsctl
   

4. *Run the Script:*

   - To see the manual page:
     ./internsctl manual
     

   - To get help:
     ./internsctl --help
     

   - To check the version:
     ./internsctl --version
     

   - Example Commands:

     bash
     ./internsctl cpu getinfo
     ./internsctl memory getinfo
     ./internsctl user create john_doe
     ./internsctl user list
     ./internsctl user list --sudo-only
     ./internsctl file getinfo hello.txt
     ./internsctl file getinfo --size hello.txt
     ./internsctl file getinfo --permissions hello.txt
     ./internsctl file getinfo --owner hello.txt
     ./internsctl file getinfo --last-modified hello.txt
     
