##Unofficial Twitter SDK

**Please note, that if you are building a new app now, you should probably be using the existing Twitter & Facebook Apis in iOS 5 and greater**

While creating an app which needed simple twitter interactions I found that all of the existing libraries used OOB signon. I also found that all the libraries looked different to the Facebook login method. What I have done is using the code from the facebook-ios-sdk built something that behaves the same as the facebook-ios-sdk without using OOB login for oAuth. 

The license is Apache 2.0, as I copied a lot of code from the facebook-ios-sdk. All of the copied code is in TwitterDialog.h/.m

I also copied a lot of code from https://github.com/jaanus/PlainOAuth as the basis of this project. 

The credit here should really go to Facebook and Jaanus Kase because all I have done is put their code together and made something new.

It should be fairly self explanatory to use, but it was written quickly and might still be buggy. If you know of any bugs please tell me so I can fix them, or submit a pull request. 