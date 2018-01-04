# vscode-fonts-settings
vscode operator mono


instructions:

1. copy fonts to font folder 
2. Install VSCode Extension: Custom CSS and JS Loader
3.Save styles.css on your desktop
4. map Custom CSS and JS Loader to style file 
5. enable Custom CSS and JS Loader


linux add files to 
1.mkdir -p ~/.local/share/fonts

2.fc-cache -f
3. in Custom CSS and JS Loader
#for vs code:
sudo chown -R $(whoami) /usr/share/code
#for vs code insiders:
sudo chown -R $(whoami) /usr/share/code-insiders
#if you want to check your folder's owner:
ls -la /usr/share/code
#if you want to rollback this permissions back to root:
sudo chown -R root /usr/share/code
