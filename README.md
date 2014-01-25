# Xposed Bridge Add-on Site

## Usage

Add this as an Add-on Site to the Android SDK Manager:

* Run `android` from the command line
* Go to Tools > Manage Add-on Sites > User Defined Sites > New...

        https://raw.github.com/grantland/xposed-add-on/master/repository/addon.xml

* Install `Xposed Bridge APIs`
* Add Xposed Bridge as your compile SDK version in your `build.gradle`

        android {
            compileSdkVersion "rovo89:Xposed Bridge APIs:19"
            
            ...
        }


## Notes

sha1

    openssl sha1

File size

    wc -c 