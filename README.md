# BitBar Coinhodler
BitBar plug-in for coinhodler.io

![ScreenShot](https://raw.github.com/romanpeters/bitbar_coinhodler/master/sample.png)

BitBar for macOS: https://getbitbar.com  
Coinhodler: https://coinhodler.io

This plug-in allows you to track your Coinhodler portfolio right from the statusbar.  
Place the python file in your BitBar plug-in folder and make it executable by running `chmod +X coinhodler.5m.py`.

You should run this plug-in from the commandline if you're using it for the first time.
It will prompt you for your mnemonic backup phrase from Coinhodler.  
If you get a ModuleNotFoundError, run `pip install requests`.
