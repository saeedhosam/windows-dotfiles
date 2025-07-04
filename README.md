# INSTRUCTIONS

- `scoop install starship`
- `scoop install gcc`
- `winget install nushell`
- Add `C:\Users\<YourUsername>\AppData\Local\nvim-data\mason\bin` to your user path on Windows


```
mkdir ($nu.data-dir | path join "vendor/autoload")
starship init nu | save -f ($nu.data-dir | path join "vendor/autoload/starship.nu")
```
cmd /c mklink /D "%APPDATA%\alacritty" "%USERPROFILE%\windows-dotfiles\alacritty"
cmd /c mklink /D "%LOCALAPPDATA%\nvim" "%USERPROFILE%\windows-dotfiles\nvim"
