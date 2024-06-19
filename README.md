# Uninstall Windows 10/11 System Apps

<p>Most system apps are unnecessary and take significant storage. Uninstall those you do not need using PowerShell and the commands.</p>
<p>If you got an error, this means the app you are trying to uninstall is either unavailable on your PC, cannot be uninstalled at all, or something else happened.</p>
<p>The list of the command is updated.</p>

## How to uninstall
<ol>
  <li>Run PowerShell as administrator.</li>
  <li>Paste a command below to delete a system app you no longer wish to have.</li>
</ol>

## System apps - commands to uninstall them
**3D Builder**
```
Get-AppxPackage -allusers *3dbuilder* | Remove-AppxPackage
```
**Alarms and Clock**
```
Get-AppxPackage -allusers *windowsalarms* | Remove-AppxPackage
```
**Calculator**
```
Get-AppxPackage -allusers *windowscalculator* | Remove-AppxPackage
```
**Calendar and Mail**
```
Get-AppxPackage -allusers *windowscommunicationsapps* | Remove-AppxPackage
```
**Camera**
```
Get-AppxPackage -allusers *windowscamera* | Remove-AppxPackage
```
**Clipchamp**
```
Get-AppxPackage -allusers *Clipchamp* | Remove-AppxPackage
```
**Cortana**
```
Get-AppxPackage -allusers Microsoft.549981C3F5F10 | Remove-AppxPackage
```
**Family**
```
Get-AppxPackage -allusers *Family* | Remove-AppxPackage
```
**Feedback Hub**
```
Get-AppxPackage -allusers *WindowsFeedbackHub* | Remove-AppxPackage
```
**Get Help**
```
Get-AppxPackage -allusers *GetHelp* | Remove-AppxPackage
```
**Get Office**
```
Get-AppxPackage -allusers *officehub* | Remove-AppxPackage
```
**Get Skype**
```
Get-AppxPackage -allusers *skypeapp* | Remove-AppxPackage
```
**Get Started**
```
Get-AppxPackage -allusers *GetStarted* | Remove-AppxPackage
```
**Groove Music**
```
Get-AppxPackage -allusers *zunemusic* | Remove-AppxPackage
```
**Maps**
```
Get-AppxPackage -allusers *Maps* | Remove-AppxPackage
```
**Microsoft Office Hub**
```
Get-AppxPackage -allusers *MicrosoftOfficeHub* | Remove-AppxPackage
```
**Microsoft Solitaire Collection**
```
Get-AppxPackage -allusers *solitairecollection* | Remove-AppxPackage
```
**Mixed Reality**
```
Get-AppxPackage -allusers *MixedReality* | Remove-AppxPackage
```
**Money**
```
Get-AppxPackage -allusers *bingfinance* | Remove-AppxPackage
```
**Movies & TV**
```
Get-AppxPackage -allusers *zunevideo* | Remove-AppxPackage
```
**News**
```
Get-AppxPackage -allusers *bingnews* | Remove-AppxPackage
```
**OneNote**
```
Get-AppxPackage -allusers *onenote* | Remove-AppxPackage
```
**Phone Companion**
```
Get-AppxPackage -allusers *windowsphone* | Remove-AppxPackage
```
**People**
```
Get-AppxPackage -allusers *people* | Remove-AppxPackage
```
**Power Automate Desktop**
```
Get-AppxPackage -allusers *PowerAutomateDesktop* | Remove-AppxPackage
```
**Photos**
```
Get-AppxPackage -allusers *photos* | Remove-AppxPackage
```
**Spotify**
```
Get-AppxPackage -allusers *SpotifyAB.SpotifyMusic* | Remove-AppxPackage
```
**Sports**
```
Get-AppxPackage -allusers *bingsports* | Remove-AppxPackage
```
**Store**
```
Get-AppxPackage -allusers *windowsstore* | Remove-AppxPackage
```
**Teams**
```
Get-AppxPackage -allusers *Teams* | Remove-AppxPackage
```
**Todos**
```
Get-AppxPackage -allusers *Todos* | Remove-AppxPackage
```
**Voice Recorder**
```
Get-AppxPackage -allusers *soundrecorder* | Remove-AppxPackage
```
**Weather**
```
Get-AppxPackage -allusers *bingweather* | Remove-AppxPackage
```
**Xbox**
```
Get-AppxPackage -allusers *Xbox* | Remove-AppxPackage
```

<br>
