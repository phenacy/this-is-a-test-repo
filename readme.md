[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15234542&assignment_repo_type=AssignmentRepo)
# Dev_Setup
### Setup Development Environment ###

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

Sources: Documentations of VSCode, Python, Flutter, Dart, MYSQL, GIT, and Windows 11

### Select Your Operating System (OS): ###
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

Step 1: Create Windows 11 Installation Media
   1. Download the Media Creation Tool:
      - Go to the Windows 11 download page: https://www.microsoft.com/software-download/windows11.
      - Under the "Create Windows 11 Installation Media" section, click "Download now".

      ![alt text](<windows download page.jpg>)

   2. Run the Media Creation Tool:
      - Open the downloaded Media Creation Tool executable file.
      - Accept the license terms.

      ![alt text](<license agreement.png>)

   3. Set Up the Media Creation Tool:
      - Choose the language, edition, and architecture (64-bit) and press next.

      ![alt text](language.png)

      - Select "USB flash drive" as the media to use. Alternatively, you can choose "ISO file" if you want to create a bootable DVD.
 
      ![alt text](<media to use.png>)

   4. Create the Installation Media:
   ![alt text](<select usb drive.png>)
   - Insert a USB flash drive with at least 8 GB of storage.
   - Select the USB drive from the list and click "Next".

   ![alt text](<downloading windows 11.png>)
    
   - The tool will download Windows 11 and create the bootable USB drive.
   - After that click finish

   ![alt text](<click finish.png>)

Step 2: Install Windows 11 Using the Installation Media
   1. Prepare Your PC:
      - Back up all important data.
      - Ensure your PC meets the Windows 11 system requirements.
   2. Boot from the USB Drive:
      - Insert the bootable USB drive into your PC.
      - Restart your PC and enter the BIOS/UEFI settings (commonly accessed by pressing a key like F2, F12, Delete, or Esc during startup).
      - Change the boot order to boot from the USB drive first.

      ![alt text](bootmenu.png)

   3. Start the Installation Process:
      - Save the changes and exit the BIOS/UEFI settings. Your PC should now boot from the USB drive.
      - The Windows Setup screen will appear. Select your language, time, and keyboard preferences, and click "Next".

      ![alt text](<windows setup.png>)

      - Click "Install now".
       
      ![alt text](<install now.png>)

   4. Enter Product Key:
   - If prompted, enter your Windows 11 product key. If you are upgrading from Windows 10, you may skip this step as the activation should be automatic.

   ![alt text](<product key.png>)

   5. Select Installation Type:
      - Choose "Custom: Install Windows only (advanced)" for a clean installation.

      ![alt text](<custom installation.png>)

      - choose windows type and click next.

      ![alt text](<windows type.png>)

   6. Partition the Drive:
      - Select the partition where you want to install Windows 11. You can delete existing partitions to create a new one, but this will erase all data on the selected partition.
       
      ![alt text](<drive partition.png>)

      - Click "Next" to start the installation.

Step 3: Complete the Installation
   1. Follow On-Screen Instructions:
      - Windows 11 will now be installed on your PC. The process might take some time and your PC will restart several times.
   2. Set Up Windows 11:
      - After installation, you will be guided through the initial setup process. Configure your preferences, sign in with your Microsoft account, and set up any additional settings.

      ![alt text](<windows 11.png>)


### Install a Text Editor or Integrated Development Environment (IDE): ###
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download


Steps to Download and Install VS Code on Windows
   1. Download VS Code:
      - Go to the Visual Studio Code download page: https://code.visualstudio.com/Download.
      - Under the "Download Visual Studio Code" section, click "Download for Windows".
      - This will start the download of the VS Code installer (VSCodeUserSetup-x64-1.X64-1.XX.X.exe).

      ![alt text](<VS Code download page.png>)

   2. Run the Installer:
      - Open the downloaded VS Code installer.
      - Run the VS Code installer (VSCodeUserSetup-x64-1.X64-1.XX.X.exe).
      - The installer wizard will appear.
   
   3. Installation Prompt:
      - Accept the license agreement and click next.

      ![alt text](<vscode license agreement.png>)

      - Choose the location where you want the VS Code installation to be kept. Accept the default location and click next.

      ![alt text](<vscode location.png>)

      - Accept the default Start Menu Folder and click Next.

      ![alt text](<default start menu.png>)

      - Select additional tasks (optional but recommended):
      - Click on Create a Desktop icon.
      - Click on Add to path (important to use the command line).
      - Click register code as an Editor for supported files.
      - Adding “Open with Code” action to the Windows Explorer context menu.
      - Adding “Open with Code” to the directory context menu.
      - Click next.

      ![alt text](<additional features.png>)

      - The installation will begin. Click on the install button.
      - After clicking install, it should take about one minute to install VS Code on your device.

      ![alt text](<installing vscode.png>)
      
   4. Finish Installation:
      - After installation, a setup window will appear. Tick on Launch VS Code and click Finish.

      ![alt text](<vscode finish installation.png>)



### Set Up Version Control System: ###
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com


sample Repo with git ignore: https://github.com/Johnnytash/this-is-a-test-repo.git.

Step 1: Download and Install Git

   1. Download Git for Windows:
      - Go to the Git download page: https://git-scm.com/downloads and download the latest version for your operating system.

      ![alt text](<git download page.png>)

   2. Run the Installer:
      - Open the downloaded Git installer.
      - Run the Git installer (Git-2.38.0-64-bit.exe).
      - The installer wizard will appear.
      - Accept the license agreement and click next.

      ![alt text](<git installer.png>)

      - choose the location where you want the Git installation to be kept. Accept the default location and click next.

      ![alt text](<git location.png>)

   3. Follow the Installation Wizard:
        - Choose the default options or customize the installation according to your preferences. Some key settings to note:
           - Adjusting your PATH environment.
           - Choosing the HTTPS transport backend.
           - Configuring the line-ending conversions.
           - Choosing the default Git editor.

           ![alt text](<git additional features.png>)

   4. Start folder:
      - You’ll be prompted to create a start folder. Leave it as is and click Next.

      ![alt text](<Start folder.png>)

   5. Text editor:
      - Choose a text editor to use with Git. Click on the drop-down menu to pick the text editor you like to use like Vim, Notepad++, etc, and click Next.

      ![alt text](<git text editor-1.png>)

   6. In the next steps choose all default options and click finish

   ![alt text](<git finish.jpg>)

   7. Verify the Installation:
      - Open Command Prompt or Git Bash and run git –version
         
      ![alt text](<git verification.png>)

Step 2: Configuring Git
   - Open a terminal or command prompt (Git Bash).
   - Set your username and email: [git config --global user. name "Your Name"] [git config --global user.email "your.email@example.com"]

Step 3: Create a GitHub Account
   - Sign up for a GitHub account at GitHub. https://github.com
   - Enter your information:
      - Unique username
      - Email address
      - Password
      - Confirm password
      - Create GitHub account
   - Click on the link to verify your email address.

step 4: Initialize a Git repository
1. Create a new repository on GitHub:
   - Go to your GitHub profile page and click on your profile picture.
   - Go to your profile.
   - Click on your repositories.
   - Click on “Create new repository”.
   - Fill in the details:
     - Repository name
     - Repository description
     - Select “Public”
     - Select “Initialize this repository with a README”(optional)
     - Add .gitignore (optional)
     - Click on “Create repository”.
     - Choose a license (optional)

2. Click "Create repository"

![alt text](<create repository.png>)

step 5: Cloning Git Repository
   - Copy the repository URL from the GitHub page.
   - Open Git Bash or Command Prompt.
   - Run git clone [repository URL](https://github.com/Johnnytash/this-is-a-test-repo.git)
   - navigate to the cloned repository and run git status to check if the repository is cloned successfully.
   - verify the cloning with the ls command

Step 6: Commit and Push Changes
 - Create a new file: [touch example.txt]
 - Add content to the file: [nano example.txt]
 - Save and exit the editor (for nano, press Ctrl+X, then Y, and Enter).

 ![alt text](<nano text.png>)

 - Check the status of your repository: [git status]
 - Add the new file to the staging area: [git add example.txt]
 - Commit the changes: [git commit -m "Add example.txt"]
 - Push the changes to the remote repository: [git push -u origin master]

 ![alt text](<git push.png>)

 - git ignore file

  ![alt text](<git ignore file.png>)



### Install Necessary Programming Languages and Runtimes: Python, Dart, and Flutter SDK ###
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.


INSTALLING  PYTHON
step1: Download python installer
   - Go to https://www.python.org/downloads/
   - Download the latest version of Python for Windows.
   - Select the installer that corresponds to the version of Python you want to install.

   ![alt text](<python landing page.png>)

step2: Run the installer
  -  Open the downloaded installer file.
  -  Run the installer.
  - Check the box that says "Add Python to PATH".
  - Click "Install Now".

  ![alt text](<install python.jpg>)

step3: Verify Installation
  - Open Command Prompt or Git Bash.
  - Run python --version
  - Verify the installation by checking the version number.

  ![alt text](<python version.png>)


DOWNLOADING DART

step1: Visit the Dart SDK Download Page:
  - Go to https://www.dartlang.org/downloads
  - Download the latest version of Dart for Windows.
  - Select the installer that corresponds to the version of Dart you want to install.

step2: Install Dart SDK on Windows
1. Download the Dart SDK:
  - Click on the "Download Dart SDK" button for Windows.
  - Choose the .zip file for Windows and download it.

  ![alt text](<dart zip file.png>)

2. Extract the ZIP File:
  - Extract the downloaded ZIP file to a desired location on your computer, e.g., C:\dart-sdk.

  ![alt text](<dart extract.png>)

3. Update Your PATH Environment Variable:
  - Open the Start Search, type in env, and select "Edit the system environment variables".
  - In the System Properties window, click on the "Environment Variables" button.
  - In the Environment Variables window, find the Path variable in the "System variables" section, select it, and click "Edit".
  - Click "New" and add the path to the bin directory inside the extracted Dart SDK folder (e.g., C:\dart-sdk\bin).
  - Click "OK" to close all the windows.

  ![alt text](<add to path.png>)

Step 3: Verify Dart Installation
  - Open Command Prompt or Git Bash.
  - Run dart --version
  - Verify the installation by checking the version number.

  ![alt text](<dart verification.png>)


DOWNLOAD FLUTTER SDK

Step 1: System Requirements:
  - Windows 10 or later(64-bit).
  - Disk Space: 1.64 GB (not including disk space for IDE/tools).
  - Tools: Flutter depends on these tools being available in your environment.
     - Git for Windows
     - The choco command, if you use Chocolatey for package management

Step 2: Download Flutter SDK:
   - Go to https://flutter.dev/docs/get-started/install/windows
   - Download the latest version of Flutter for Windows.
   - Select the installer that corresponds to the version of Flutter you want to install.

   ![alt text](<flutter download page.png>)

Step 3: Install Flutter SDK on Your Operating System
1. Download the Flutter SDK:
  - Click on the "Download Flutter SDK" button for Windows.
  
  ![alt text](<flutter for windows.png>)

  - Choose the .zip file for Windows and download it.

  ![alt text](<flutter zip file.png>)

2. Extract the ZIP File:
   - Extract the downloaded ZIP file to a desired location on your computer, e.g., C:\flutter-sdk.

   ![alt text](<extract flutter zip.png>)

3. Update Your PATH Environment Variable:
   - Open the Start Search, type in env, and select "Edit the system environment variables".
   - In the System Properties window, click on the "Environment Variables" button.
   - In the Environment Variables window, find the Path variable in the "System variables" section, select it, and click "Edit".
   - Click "New" and add the path to the bin directory inside the extracted Flutter SDK folder (e.g., C:\flutter-sdk\bin).
   - Click "OK" to close all the windows.

   ![alt text](<flutter add to path.png>)

4. Verify Flutter Installation
   - Open Command Prompt or Git Bash.
   - Run flutter --version
   - Verify the installation by checking the version number.
   
   ![alt text](<flutter version.png>)

   - Run Flutter Doctor:
      - Type flutter doctor and press Enter.
      - This command checks your environment and displays a report of the status of your Flutter installation. Ensure all required dependencies are installed.

      ![alt text](<flutter doctor.png>)



### Install Package Managers: ###
   If applicable, install package managers like pip (Python).

Python (pip)
  - Ensure pip is installed and up-to-date: [python -m pip install --upgrade pip]
  - Install required packages: [python -m pip install -r requirements.txt]
  - To install a package using pip: [pip install package-name]

  ![alt text](<python pip.png>)




#### Configure a Database (MySQL): ###
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

1. Download MySQL
   - Go to the MySQL Community Downloads page.https://dev.mysql.com/downloads/installer/
   - Download the latest version of MySQL for Windows.
   - Select the installer that corresponds to the version of MySQL you want to install.

   ![alt text](<msql download page.png>)

2. Run the Installer:
   - Open the downloaded .msi file.

3. Choose Setup Type:
   - Choose a setup type (Developer Default, Server only, etc.) and click Next.

   ![alt text](<msql type.png>)

4. Check for Requirements:
   - The installer will check for and install the necessary dependencies.

   ![alt text](<msql requirements.png>)

5. Installation:
   - Click Execute to install the selected MySQL products.
   
   ![alt text](<msql products.png>)

6. Configuration:
   - Next, you need to configure the MySQL server, click "Next":

   ![alt text](<product configuration.png>)

7. Standalone MySQL Server
   - Select the "Standalone MySQL Server / Classic MySQL Replication" item and click "Next":

   ![alt text](<standalone MYSQL.png>)

8. Type and Networking 
   - Next, in the "Config Type" parameter, select "Server Computer" and click "Next":

   ![alt text](<type and networking.png>)

9. Password and authentication :
  - Select "Use Strong Password Encryption for Authentication" and click "Next":

  ![alt text](<password and authentication.png>)

10. Accounts and roles :
   - In the next window, you need to set a password for the root user (administrator). Also, here you can add other users (by clicking the "Add User" button), if necessary. After entering the password, click "Next":

11. At the next step, we leave all the default settings, and click "Next":

![alt text](<windows services.png>)

12.  MySQL server settings:
  - Next, you need to apply the MySQL server settings by clicking "Execute":

  ![alt text](<mysql server settings.png>)

13. Finish
   - Finally, click "Finish" to complete the installation.



### Set Up Development Environments and Virtualization (Optional): ###
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

A. Using Docker
Step 1: Install Docker
  - Download and install Docker Desktop from the Docker website.
  - Follow the installation instructions and start Docker Desktop.
Step 2: Verify Docker Installation
  - Open Command Prompt or Git Bash.
  - Run docker --version
  - Verify the installation by checking the version number.

B. Using Virtual Machines
Step 1: Install Virtualization Software
  - Download and install VirtualBox from the VirtualBox website.
  - VMware Workstation Player: Download and install from VMware.
Step 2: Download an OS Image
  - Download an ISO file of the operating system you want to use (e.g., Ubuntu from https://ubuntu.com/download ).
step 3: Create a Virtual Machine
  - Open VirtualBox or VMware Workstation Player.
  - Create a new VM:
   - In VirtualBox, click "New" and follow the prompts.
   - In VMware Workstation Player, click "New" and follow the prompts.
  - Configure VM settings:
   - Allocate memory (RAM) and CPU cores.
   - Create a virtual hard disk.
  - Install the OS:
   - Start the VM and select the downloaded ISO file.
   - Follow the installation instructions for the chosen operating system.
 


### Explore Extensions and Plugins: ###
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

Visual Studio Code (VS Code) Extensions
VS Code is a highly customizable text editor with a vast ecosystem of extensions. Here are some essential extensions:
   - Python: Provides IntelliSense, linting, and debugging for Python files.
   - Pylance: Enhances Python language support.
   - ESLint: Detects and fixes linting issues in JavaScript and TypeScript files.
   - Stylelint: Detects and fixes style issues in CSS and SCSS files.
   - Prettier: Formats code automatically based on defined rules.
   - GitLens: Visualizes and provides Git integration.
   - Docker: Manages Docker containers, images, and Dockerfiles within VS Code.
   - SQLTools: Interacts with databases directly from VS Code.
   - C/C++: Enhances C/C++ language support.
   - HTML CSS Support: Enhances HTML/CSS development with class name completion and live previews.
   - IntelliSense for CSS class names in HTML: Adds autocomplete for CSS class names.
   - Code Runner: Runs code snippets or entire files directly from VS Code.
   - Live Server: Launches a local server with live reload for static and dynamic pages.
   - HTML Snippets: Provides quick access to common HTML code snippets.
   - CSS Peek: Navigate to CSS definitions from HTML files.
   - Live Server: Launches a local server with live reload for static and dynamic pages.
   
![alt text](extensions.png)



### Reflection on Challenges ###
Challenges Faced:
  - Configuring Git: Understanding Git commands and initial setup took some time.
  - Python Installation: Ensuring Python was added to the PATH correctly required careful attention.
  - Docker: Installing and configuring Docker took some time.
  - MySQL Installation: Configuring the MySQL server and setting up the root password was challenging without prior database experience.

Solutions:
 - Git: Followed detailed tutorials and referred to Git documentation.
 - Python: Added Python to the PATH environment variable.
 - Docker: Followed detailed tutorials and referred to Docker documentation.
 - MySQL: Used MySQL official documentation and community forums for troubleshooting.


### Sample github repository: ###
https://github.com/Johnnytash/this-is-a-test-repo.git



### Document Your Setup: ###
   Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 

#Deliverables:
- Document detailing the setup process with step-by-step instructions and screenshots where necessary.
- A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore).
https://github.com/Johnnytash/this-is-a-test-repo.git

- A reflection on the challenges faced during setup and strategies employed to overcome them.

#Submission:
Submit your document and GitHub repository link through the designated platform or email to the instructor by the specified deadline.

#Evaluation Criteria:**
- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.
