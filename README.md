
# Default Hosts File for Windows 10

## How to Reset Hosts File Back to Default in Windows 10


Every Windows version comes with a Hosts file which provides a simple mechanism to redirect website to IP address. If the HOSTS file is modified incorrectly or maliciously, it can break your Internet. In this tutorial we’ll show you how to easily reset the HOSTS file (C:\Windows\System32\drivers\etc\hosts) back to default in Windows 10.

### How to Reset Hosts File Back to Default in Windows 10?

By default, the HOSTS file is protected by the operating system so you’re unable to edit it without admin rights. Here we’re going to open the HOSTS file with Notepad and restore its content back to default:
# Documentation


#### Click the Start button and type notepad. Right-click the Notepad app appeared in the search result, and then select “Run as administrator“.
![How to open Notepad in administrator mode in Windows](https://www.top-password.com/blog/wp-content/uploads/2018/10/open-notepad-as-administrator.png)

#### With Notepad open in administrator mode, you’re ready to open the HOSTS file. Click on the File menu and select Open.
![How to open Hosts file in Notepad opened in Administrator mode](https://www.top-password.com/blog/wp-content/uploads/2018/11/notepad-file-menu.png)

#### Browse to the directory C:\Windows\System32\drivers\etc\hosts. Change the file filter drop-down box from “Text Documents (*.txt)” to “All Files“, and select the HOSTS file and click Open.
![Location of Hosts File](https://www.top-password.com/blog/wp-content/uploads/2018/11/open-the-hosts-file.png)

#### Now, paste the [following text](https://raw.githubusercontent.com/avasthi-git/default-hosts-file/main/hosts) into Notepad:

```
# Copyright (c) 1993-2009 Microsoft Corp.
#
# This is a sample HOSTS file used by Microsoft TCP/IP for Windows.
#
# This file contains the mappings of IP addresses to host names. Each
# entry should be kept on an individual line. The IP address should
# be placed in the first column followed by the corresponding host name.
# The IP address and the host name should be separated by at least one
# space.
#
# Additionally, comments (such as these) may be inserted on individual
# lines or following the machine name denoted by a '#' symbol.
#
# For example:
#
# 102.54.94.97 rhino.acme.com # source server
# 38.25.63.10 x.acme.com # x client host
#
# localhost name resolution is handle within DNS itself.
# 127.0.0.1 localhost
# ::1 localhost

```

![Paste the following code](https://www.top-password.com/blog/wp-content/uploads/2018/11/reset-hosts-file-to-default.png)

#### Click on the File menu and Save. Now you’ve successfully reset the HOSTS file back to default in Windows 10.



# Hi, I'm [Ishan Avasthi!](http://ishanavasthi.in) 👋


## 🚀 About Me
I'm a 17y/o student...  


## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://ishanavasthi.in/)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/heyavasthi)
[![twitter](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/heyavasthi)
[![telegram](https://img.shields.io/badge/Telegram-Message%20me%20on%20Telegram-blue)](https://telegram.me/ishanavasthi)


## 🛠 Skills
Javascript, HTML, CSS...

