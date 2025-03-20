<h1>Automating User Account Unlocking in Active Directory with PowerShell</h1>

 

<h2>Description</h2>
In large IT environments, manually unlocking user accounts can be time-consuming, especially when multiple users frequently get locked out due to incorrect password attempts. Automating the user account unlocking process with PowerShell allows IT helpdesk teams to resolve account lockouts quickly and efficiently, reducing downtime and improving user productivity.
<br/>
<br/>

<h2>Benefits of Automating User Account Unlocking:</h2>
<br/>

✅ Time-saving – Eliminates the need for manual intervention, especially during peak hours. <br/>
✅ Faster incident response – Users regain access quickly without waiting for IT support. <br/>
✅ Proactive monitoring – Can be scheduled to check for locked accounts and unlock them automatically. <br/>
✅ Logging and auditing – Keeps track of all unlocked accounts for compliance and security purposes. <br/>
✅ This script ensures that only a specific locked account is unlocked and logs the action for record-keeping. <br/>
<br />


<h2>Utilities Used</h2>

- <b>PowerShell</b> 

<h2>How to Use the PowerShell Script to Unlock a Specific User in Active Directory:</h2>
This script allows you to manually unlock a locked Active Directory (AD) user account by entering their username when prompted. <br/> <br/>

<h2>Step 1: Save the Script</h2>
1.Open Notepad (or any text editor).<br/>
2.Create the PowerShell script.<br/>
<img src="https://imgur.com/Kh1mMmD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
3.Click File → Save As.<br/>
4.In the Save as type dropdown, select All Files.<br/>
5.Name the file: Unlock-SpecificUser.ps1<br/>
6.Save the script in a directory, e.g., C:\Scripts.<br/>
<img src="https://imgur.com/xwAPN8u.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<h2>Step 2: Run the Script Manually</h2>
1.Open PowerShell as Administrator.<br/>
2.Navigate to the script location.<br/>
RUN: cd C:\Scripts<br/>
<img src="https://imgur.com/XX04bzX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
3.Run the script.<br/>
RUN: \Unlock-SpecificUser.ps1<br/>
<img src="https://imgur.com/EanNr2A.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
4.Enter the username of the locked account when prompted.<br/>
<img src="https://imgur.com/6eOexes.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
5.The selected account will be unlocked.
<br/>
<br/>
<br/>
<br/>
<h2>Optional: Create a Shortcut for Easy Access</h2>
To simplify running the script:<br/>

1.Right-click on the desktop → New → Shortcut<br/>
2.In Location, enter: powershell.exe -ExecutionPolicy Bypass -File "C:\Scripts\Unlock-SpecificUser.ps1"<br/>
3.Click Next, name it Unlock AD User, and click Finish.<br/>
<img src="https://imgur.com/jfa57pz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/><br/>
4.Right-click the shortcut → Properties → Advanced → Check Run as Administrator → OK.<br/>


<h2>Now, you can just double-click the shortcut and enter a username when needed!</h2>
<img src="https://imgur.com/zQ5sTZf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>





<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
