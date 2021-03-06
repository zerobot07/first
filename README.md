*Short introduction to your problem.*

__Input code:__
```vb
REM The code your entered in the input text area
```

__Output code:__
```arduino
/* The code outputted by the script, 'none' otherwise */
```

__Error:__
```js
/* Any error outputted by the page or the console, 'none' otherwise */
```
# DroidCam v1.0
## Author: https://github.com/thelinuxchoice/DroidCam
## IG: https://www.instagram.com/linux_choice
### Don't copy this code without giving me the credits, nerd! 

Script to generate an Android App to take photos from Cameras using Camera2 function on API 21.

DroidCam uses Camera2 function by Hamed ZITOUN (https://github.com/botyourbusiness/android-camera2-secret-picture-taker) 

![dc](https://user-images.githubusercontent.com/34893261/50490362-e24e5c80-09f3-11e9-9a14-db89d6f2c0c9.png)

### Features:
#### 2 Port Forwarding options (Ngrok or using SSH Tunneling with Serveo.net)
#### Obfuscated URL by Tinyurl
#### Fully Undetectable

## Legal disclaimer:

Usage of DroidCam for attacking targets without prior mutual consent is illegal. It's the end user's responsibility to obey all applicable local, state and federal laws. Developers assume no liability and are not responsible for any misuse or damage caused by this program 

### Auto Install:

```
# bash install.sh
```

### Installing on Kali Linux:
```
Install dependencies:
# apt-get update
# apt-get install default-jdk apksigner

For x86:
# apt-get install libc6-dev-i386 lib32z1

For AMD64:
# apt-get install lib32z1 lib32ncurses6 lib32stdc++6

Download SDK-Tools:
# wget https://dl.google.com/android/repository/sdk-tools-linux-4333796.zip
#mkdir -p $HOME/Android/Sdk
# unzip sdk-tools-linux* -d $HOME/Android/Sdk

Install SDKMAN
# curl -s "https://get.sdkman.io" | bash
# source "$HOME/.sdkman/bin/sdkman-init.sh"
# echo "Y" | sdk install java 8.0.191-oracle
# sdk use java 8.0.191-oracle
# sdk install gradle 2.14.1
# sdk use gradle 2.14.1

# echo "y" | $HOME/Android/Sdk/tools/bin/sdkmanager "platforms;android-25" "build-tools;25.0.1" "extras;google;m2repository" "extras;android;m2repository"

# git clone https://github.com/thelinuxchoice/droidcam
# cd droidcam
# bash droidcam.sh
```

### Donate!
Support the authors:
### Paypal:
https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=CLKRT5QXXFJY4&source=url
### LiberaPay:
<noscript><a href="https://liberapay.com/thelinuxchoice/donate"><img alt="Donate using Liberapay" src="https://liberapay.com/assets/widgets/donate.svg"></a></noscript>
