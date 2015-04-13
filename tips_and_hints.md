# Tips: #

#### Q. How do I remove my eMusic Remote profile and settings? ####
A. The eMusic Remote 1.0 profile directories can be removed manually, check below here for platform specific paths:
> This data is stored in your profile folder, which is located in one of the following locations depending on your operating system:
| Windows 2000, XP | Documents and Settings\

&lt;UserName&gt;

\Application Data\eMusic |
|:-----------------|:--------------------------------------------------------------------|
| Windows NT | WINNT\Profiles\

&lt;UserName&gt;

\Application Data\eMusic |
| Windows 98, ME | Windows\Application Data\eMusic\ |
| Mac OS X | ~/Library/Application Support/eMusic Download Manager |
| Linux and Unix systems | ~/.emusic |

#### Q. Why doesn't the Linux installer launch? ####
A. You need to change the execute bit on the file: chmod ug+x

#### Q. Does the Linux installer require root access? ####
A. No it should not, but you will need to change the execute bit on the file: chmod ug+x


#### Q. How do I install Flash player on Linux? ####
A. For universal Mozilla support you can also opt to install the plugin in the following directory and skip step 3:
~/.mozilla/plugins

  1. [download Flash 9 here](http://www.adobe.com/go/getflashplayerlinux):
  1. run flashplayer-installer and follow prompts
  1. when prompted for application directory and you used the installer:
/%YOUR\_INSTALL\_PATH%/emusicremote/xulrunner 

**Note: the plugin will be installed into the /%YOUR\_INSTALL\_PATH%/emusicremote/xulrunner/plugins directory.**

