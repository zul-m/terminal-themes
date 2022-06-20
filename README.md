# Windows Terminal Themes

Windows Terminal is a great tool when it comes to using Command Line Interfaces. Unlock the great potential of Windows Terminal using a custom profile that gives you a custom Sitecore theme and autocompletion on CLI commands for the Sitecore CLI as well as the XM Cloud Plugin.

## Preconditions

### Install Windows Terminal

- Go to Microsoft Store and search for Windows Terminal
- Hit Install Button
- Launch Windows Terminal

### Install Powershell Version 7.7.2
- Go to Microsoft Store and search for Powershell
- Hit Install Button
- Restart Windows Terminal (close and open)

### Make Powershell 7.7.2 the standard shell
- Open Settings
- In Startup Selected PowerShell as your default profile

### Install Oh My Posh

- In Terminal run: `Install-Module posh-git -Scope CurrentUser`
- Confirm that you trust the repository with  `a`

- Run: `Install-Module oh-my-posh -Scope CurrentUser`
- Confirm that you trust the repository with `a`

- Run: `Install-Module -Name PSReadLine -AllowPrerelease -Force`

- Run: `Install-Module -Name Terminal-Icons -Repository PSGallery`

#### Test Oh My Posh

- In Terminal run: `Set-PoshPrompt`

### Install Nerd Fonts
- Download CascadiaCode file or go to Nerdfonts.com and download Caskaydia Cove Nerd Font
- Install Fonts in zip file

- In Windows Terminal
- Go to Settings
- Go To Appearance
- Select Font face "CaskaydiaCove NF"

#### Test
- In Terminal glyphs should be shown now

### Get available Posh Themes (optional)
That step will download available Themes

- In Terminal run: `Get-PoshThemes`

### Switch Theme (optional)
- In Terminal run: `Set-PoshPrompt -Theme free-ukraine`

## Use Sitecore branded theme and profile

### Change the Theme 
- Download *sitecore.omp.json*
- Copy file to that path: C:\Users\<username>\AppData\Local\oh-my-posh\themes\

### Change the Profile
- Download *Microsoft.PowerShell_profile.ps1*
- Copy file to that path: C:\Users\<username>\Documents\PowerShell\Microsoft.PowerShell_profile.ps1 and overwrite the extisting (if any)
- Open profile file and adjust the path to the theme according to your theme file location

