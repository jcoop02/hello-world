# hello-world
CIS 141 Technical Blog
﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿﻿# **CIS _141_ Tech Blog**
## Josh Learn


### **Emoji Bio **
Age :three::eight:

Look :boy: Feel :older_man: Am :man:

Things I love:
* :baseball:
* :sushi:
* :art:
* :books:
* :pisces:
* :milky_way:

##### Skill 1.1 - Prepare for Installation Requirments


WARM-UP: How many computers are in room V-129? My total number was 90. I counted roughly 34 computers or laptops, plus 26 people in which I assume each is carrying a smartphone . I consider humans or the human brain to be a computer. Probably the quickest processor on the planet. Then I threw in a few smart watches just for good measure.

PROMPT: The primary user of this computer is my nephew at hos house.

 Computer specs:

                 Processor- 1.80GHz and 2.40GHz   vs.  1GHz required

                 Memory- 8GB RAM   vs.  2GB  required

                 Hard Disk- 1TB 64bit ver.  vs.   20GB  required

                 Graphics- NVIDIA GT745M  vs.   DirectX9  required

                 Display Res- 1920 x 1080   vs.   800x600 required


  I chose to do an In-place Installation of Windows 10 Home. There were no device or OS obstacles that would prevent from doing so.
  The previous or existing OS was Windows 8. This allowed for a pretty seamless upgrade using the setup wizard and I chose the home edition because the user will only be using
  the computer for basic word processing and internet browsing.


#####Skill 1.2- 
1. Why would a user be interested in multiple partitions on a hard drive?  Use a Windows tool (GUI or CLI) to create a partition and describe the steps that you took to create multiple partitions.
   - It allows a user to manage their files or separate them from other main drives they use.
       -  Open Disk Management
       -  We Chose an unallocated disk partition and we shrunk it down to size to create a different partition named R.
 
2. Describe each step that requires "user attention" during the clean installation of Windows 10.
    -  Enter the Product Key to Activate Windows 8.1 Key entry:   NG4HW-VH26C-733KW-K6F98-J8CK4           
    - Choose Language, Time Format, Keyboard input method
    - Choose Upgrade or Custom Install
    - Choose where you want to install on what drive.
    - Finish  Personlize with different settings
3.  What is one Windows Feature that you chose to add after installation?  How did you add that feature? 
         
- I chose to install a Telnet Client and Windows hypervisor platform
-  I went to search and I used the Windows Features box to check the features to add.
###Skill 1.3 Prompt
1. Create a list of hardware that a user might have that require a driver installation.
 - A New Mouse, keyboard, printer, speakers

2. Locate a device from your list (for example, printer or external storage) and install it on Windows 10 (VM in class, machine at home, maybe the host machine in class?)
 - Printer
3. Locate the version of the driver and see if it is the most current version available (in the case of the printer, check the manufacturer website). If necessary update the device.
       
4. Disable the device.  Does this affect Windows performance?  What happens when you disable other devices?  Try disabling your network card - how was that experience?  
       - It creates errors when trying to run in other programs
5. Why would I disable updates over metered connections?  Capture a screenshot of the screen on which you disabled this feature.
     - So you don't download unnecessary updates when you don't need them on a metered connection.
    -  

6. Perform a "rollback" of a driver update.  Note, you will need to access a different USB device if you have been working with a printer.
7. After installing a USB microphone, a system has extremely poor performance.  How would you check to see if the performance issues are related to the USB microphone?
     - You can go to device manager and disable the USB microphone to see if there is any affect.



#####Skill 1.4

How to personalize smart tiles: right click start menu, then hit Personalize. You can expand, shrink, make certain apps show live feed (twitter), group apps
together(organization).
How to set up multiple Desktops: click the task view button on the task bar, then click new desktop on the lower right. To switch between desktops, hit the task
view button and then choose the appropriate desktop you want to switch too.

How to configure action center and taskbar:

 * you can access the action center by swiping from the right on a tablet or by clicking the notification incon in the system tray.
  * Quick action tiles enable you to configure Rotation Lock, WiFi, Location, Bluetooth, VPNs
  * if you wanted to configure what tiles you see in collapsed view, click all settings, choose system, and click "Notifications and Actions" tab

  
#####Configure Cortana

To configure Cortana on a clean install of Windows 10, there are several tasks you need to complete. 

To set up the initial configuration, perform the following steps:
- Click the Start Menu, or press the Windows key
- Click All Apps
- Click Cortana
- Click Use Cortana
- Select Yes/No for Speech, Inking, and Typing Personalization options

To pin Cortana to the Taskbar, perform the following steps:
- Right-click the Taskbar
- Click Cortana
- Select from the Hidden, Show Icon, and Show Search Box options

To configure voice activation, perform the following steps:
- Press Windows + S to open Cortana
- Click the Notebook icon
- Click Settings
- Select On/Off on the Hey Cortana selector

To configure voiceprint recognition, perform the following steps:
- Press Windows + S to open Cortana
- Click the Notebook icon
- Click Settings
- Click Learn My Voice
- Click Start
- Follow instructions given by Cortana

#####Configure Accessibility

Ease of Access allows the user to configure most Accessability options. These settings are designed to provide better options for users with learning disabilities, physical disabilities, or other impairments.

To open Ease of Access before logon, perform the following steps:
- Power on the PC
- Click to dismiss the Lock Screen
- Click Ease of Access icon in lower right corner

To open Ease of Access after logon, perform the following steps:
- After logon, search for and open Ease of Access from Start Menu

The following Accessability settings can be configured from the Ease of Access window:
- Narrator
- Magnifier
- On-Screen Keyboard
- High Contrast
- Sticky Keys
- Filter Keys

To configure Narrator, select the desired setting from each of the following on-screen options:
- On/Off
- Start Automatically
- Choose Voice
- Speed/Pitch
- Intonation Pauses
- Voice Hints for Controls and Buttons
- Voice characters when typed
- Voice words when typed
- Lower volume of other apps
- Play Audio Cues
- Highlight Cursor
- Configure for Braille display (beta)

To configure Magnifier, select the desired setting from each of the following on-screen options:
- Follow Cursor/Narrator
- Select View

### Skill 1.5 Prompt
What Is UAC?
   -  User account control is a feature that was designed to prevent unauthorized changes to your computer. When functions that could potentially affect your computer's operation are made.
   -  It is important because it prevents people from having certain administrator permission to alter the windows settings.
   -  Introduced with Microsoft's Windows Vista[1] and Windows Server 2008 operating systems, with a more relaxed[2] version also present in Windows 7
   -  Its essential for sierra college network of computers to have this feature because it prevents people from ruining the registry.
   
## Enterprise Implementation
    - LSDO   L- Locally S-Site D-Domain OU-Organizational   - Increasing in permissions
    - Group Policy Editor  - It Changes the permission for a group of users and changes how much control they have as a user.
##  GPEdit Challenge
   1.  You can block Microsoft accounts going through the registry under security settings > security options > and choose enable or disable account.
   2.  An enforced password of 10 or more characters.
   3.   Disable secured desktop- if you drop your security toggle down one rung, it will say " do not dim my desktop"

###  Skill 2.1 Technical Blog Prompt


 Create a "Top 5" list of Windows 10 networking best practices, tips, tricks and troubleshoot	KEEP UNWANTED SOFTWARE OFF PCS - disables popups as well as frees up processor speed

#### STOP USING SMBV1 PROTOCOL - Microsoft recommendation to disable due to ransomware outbreaks

####SOLVE NETWORK PROBLEMS WITH A ONE-CLICK RESET - Anniversary update enabled to see network status at a glance

####	DISABLE THE BUILT-IN ADMINISTRATOR ACCOUNT - Reduce the attack surface on PC

####	PROTECT REMOVABLE STORAGE DEVICES WITH ENCRYPTION - File cannot be stolen if lost, i.e. security.

Link: {\field{\*\fldinst{HYPERLINK "https://www.zdnet.com/article/windows-10-networking-and-security-tips/"}}{\fldrslt https://www.zdnet.com/article/windows-10-networking-and-security-tips/}}\


### Skill 2.2 Technical Blog Prompt
 
- Scenario 1: Creating a Large Volume

You have a new desktop running Windows 10. 
However, you try to copy your file repository and find out that you do not have enough disk space. 
You have 400 GB of free disk space on your C drive and you have 3 smaller 500 GB drives. 
What can you do?

 assuming I would create a storage pool and reallocate my repository to a new location after determining how much space is actually needed for the repository.  

- Scenario 2: Configuring a Storage Space/Storage Pool

You create a new storage pool for the following disks on your Windows 10 computer:
Serial ATA (SATA): 1 TB
Serial Attached SCSI (SAS): 1 TB
SATA and SAS are two different types of drives with different connectors/interfaces.
What is the maximum size you can allocate for your new storage space?

	With 1TB SATA you can set the storage size to 2 TB and with 1 TB SAS you could also a have 2TB pool combined with each other to make 4 TB


# Skill 2.3 Technical Blog Prompt

### **_LAB 9  Installing a virtual printer_**

**1.2.1 How many printer devices are installed on this machine?**      3 

**2.1.1
How many printing devices are now displayed in the Devices and Printers window?**    4

**3.1.1
What is the title of the new window that has appeared?** Save Print Output As

**3.1.2
What extension is placed on the Printed File document now saved on the desktop?**     .prn


**3.1.3
Besides the original types message, what else is displayed in this Printed File?**  Printer file/ Page 1


**4.1.1
Which device has become the default printer now that the Virtual Printer has been removed?**
Microsoft print to PDF


### **_LAB 10 Share a Virtual Printer_**


**1.2.1
How many printer devices are installed on this machine?**        3 

**2.1.1
How many printing devices are now displayed in the Devices and Printers window?**     4

**3.1.1
What is now shown in the description at the bottom of the window?**   Shared emoji w/ green check

**4.1.1
How many printer devices are installed on the PC1 machine?**   3

**4.1.2
How many printers are now listed in the Devices and Printers window?**     4

**4.1.3
What is the title of the window that opens?**   Save print output as

**4.1.4
Did the file appear on the desktop?**    Yes


### **_LAB 12 Configure Local User File Sharing_**

**3.1.1 Question Bank 1 
 Which account type was created for the TEST user account?** 
 Standard user

 **Why would someone want to change a user account from the default account type to an Administrator account? What benefits does the Administrator account provide?**
 Gives the user more access and/or control over security and settings

**5.1.1 Question Bank 2 
 Who is the folder currently shared with?**    Student

**5.1.2 Question Bank 3 
 Which three user accounts can this directory be shared with?**    Student/test/everyone

**5.1.3 Question Bank 4 
 Which two accounts are now listed?** Student/test

**6.1.1 Question Bank 5 
 What message appears?**   Access is denied

**Why is the TEST user unable to alter this file?**  Was not designated as admin privilege.

# Skill 2.4 Technical Blog Prompt

*You work for a small business of 25 employees, split between two offices that are in different buildings but share a parking lot.*
 
*You have been tasked with deploying Microsoft Office to all machines, Adobe CS Suite to the Marketing team, and QuickBooks to the Accounting Team.  You also want to allow users to selectively install Adobe Acrobat.*
 
*What would you do?*



Assuming that both buildings are on the same network and have Active Directory setup through Windows Server 2012 R2, I would use GPO's. I would assign Adobe CS Suite to the marketing container and QuickBooks to the accounting container so when the respective parties from those groups sign in, the apps will auto install on their computers. I would then put Adobe Acrobat in a shared OU so that anyone with access to our network can install it if they so choose.


# Skill 2.5 Tech Prompt

1) Joe is a new IT Director who is tasked with making sure his Windows 10 computer users can be assisted remotely. On his first day at the company, Joe was told that the Remote Assistance feature was not working for users after a new firewall was installed. What could be causing the problem and how should it be addressed?

- 

2) You are an administrator at the Contoso Corporation. You have a 12-person help desk that supports about 10,000 users spread out over a 5-building campus. You don’t have enough people to provide support staff visits to a user who is having problems. Describe the actions you can take to support your company users.


- 


# Skill 3.1 Technical Blog Prompt
1. You are an IT manager and would like to use a virtual machine to keep up to date on the latest development in Windows 10 and access the preview builds.  How would you go about doing this?
2. As an IT manager, one of the departments you support is Physical Plant Operations.  They use a specialized application to run power generators that does not need access to the Internet or require any operating software updates.  Which branch of Windows 10 will you recommend for use by the Physical Plant Operations department?  Why?
3. As an IT manager, you have developed a custom image of Windows 10 that is deployed to all general users.  You do not want the users to be able to install additional software, including applications found in the Windows Store.  How could you prevent users from installing apps from the Windows Store?

#Skill 3.2 & 3.3 Technical Blog Prompt


1)  You are an IT manager and several computers belonging to support staff were recently upgraded from Windows 7 Pro to Windows 10 Enterprise.  You have received several complaints that "their computers are slow", "apps stop responding" and "websites are slow to load".  Describe the monitoring tools you would use to help diagnose the issues.

- I would use Event Viewer and Resource Monitor to diagnose the issues that I received complaints about. Event viewer uses Event logs which are accessed in the Windows Event Viewer and provide information regarding system events that occur. Event logs include information, warning, and error messages about Windows components and installed applications and actions carried out on the system. Resource Monitor
Displays more information and activity statistics relating to your system resources in real time. Similar to Task Manager but also enables you to dive deeper into the actual processes and see how they affect the performance of your CPU, disk, network, and memory
---


2) Your Sierra College instructor just gave you a free laptop (not going to happen).  You want to make sure that the contents of that machine are periodically backed up and that you have access to previous versions of files.  Describe the data recovery strategies you would implement on your new machine.

- I would start by making an image backup of your computer. By creating an image of your computer, you’ll have a known point to which you can always return should anything go wrong in the future. Next I would make a recovery drive using a USB flash drive, from which I could boot my machine in order to restore the image that I made in the first step. Plus you can Restore Individual Files from a Windows Image Backup using Windows backup tool. 





