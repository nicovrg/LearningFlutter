# LearningFlutter

## Setup

    
    Install flutter:

        1 - git clone https://github.com/flutter/flutter.git -b stable --depth 1
        2 - export PATH="$PATH:`pwd`/flutter/bin"
        3 - flutter precache (optionnal)
        4 - flutter doctor
        Follow instructions here - https://flutter.dev/docs/get-started/install/linux

    Install Android Studio:

        1 - Install android studio
        2 - Open Tools > ADV Manager > Choose and configure an emulator
        
        Follow instructions here: https://developer.android.com/studio

    Install Xcode:
    
        Didn't bother yet, only for MacOS. Required to build IOS app.

    Add to .zshrc: 
    
        alias studio="/home/nico/Code/frameworks/android-studio/bin/studio.sh"
        export PATH="$PATH:/home/nico/Code/frameworks/flutter/bin

    Install extension for VSCode and Android Studio and then run flutter doctor.

    Usefull links:

        https://flutter.dev/docs/get-started/install/linux
        https://developer.android.com/studio/install
        https://developer.android.com/studio/run/emulator-acceleration
        https://developer.android.com/studio/run/managing-avds?utm_source=android-studio