## What is flutter

 It an open-source user-interface software development kit that was developed by Google. Flutter is used to create native-looking Android, iOS, Mac, Linux, windows applications from the same code base.

## Background of flutter / history

Flutter is an application framework that was developed by Google and the community. The application framework was released two years ago and it was written in c, c++ and dart programming languages. Also, flutter can run on the following platforms, windows, Linux, Mac, iOS, web and android. 

## Comparison of flutter and react-native

Flutter uses Dart programming which is easy to master.
React-native uses JavaScript programming which is complicated to master.

Flutter engine has most of the native components in the framework itself and it doesn’t always need a bridge to communicate with the native components.

 React Native, however, uses the JavaScript bridge to communicate with native modules, which results in poor performance.
The getting started guide for Flutter has detailed information on Integration Development Environment setup and platform setup for both iOS and Android. One can read all the required setup details on Flutter install for all platforms, Flutter has a tool called flutter doctor which can guide developers through the setup.

React Native project assumes that the developer already has all the required setup for developing for iOS and Android. There is little information on the Xcode command-line tools. Hence it's clear that Flutter offers better documentation. 

##Comparison of Flutter and Ionic 

Ionic provides a comprehensive library of mobile and desktop-optimized HTML, CSS and JS components for creating highly intuitive and interactive applications. The ionic framework can create hybrid mobile applications for cross-platforms like iOS or Android. 

 Flutter and Ionic both appear native as far as the user is concerned. However, both frameworks use the native User-Interface elements, Flutter and Ionic update the design of User-Interface elements to match the look of the platform running on such as Material Design for Android and Cupertino for iOS. Both come with the ability to access platform services and native Application Programmable Interface (APIs) via a library of pre-built plugins with a set of tools to build custom plugins

When you build with Ionic, you will learn and apply the tools and languages of the web, using a framework designed to deliver great performance on mobile, desktop, and especially, the web. However, flutter, in contrast, has chosen to go it alone, creating a self-contained ecosystem that is at odds with the common languages, toolsets, and standards found in the broader development world. 

##Flutter vs Kotlin: What are the differences?

Kotlin is a statically typed programming language targeting java virtual machine and JavaScript. Kotlin is a statically typed programming language for the  Java Virtual Machine (JVM), Android and the browser, 100% interoperable with Java.

Flutter is well known as cross-platform mobile development and Kotlin is the group under Languages. The main reason why developers consider flutter over other available technologies is because of the hot reload. whereas Inter-operable with Java was stated as the key factor in picking Kotlin.

##Why Flutter over other technologies

1.  Create beautiful, highly-customized user experiences 

2. Fast Development
Flutter was developed for high development velocity. Hot reload allows you to change your code and see it come to life is less than a second without losing the state of the application.

3. High Performance 
Flutter doesn’t require a JavaScript to bridge speed. 

4. Expressive + Flexible UI

5. Flutter moves to a widget, rendering, animation, and gestures into this framework to give you complete control over every pixel on the screen. It means you have the flexibility to build a custom design. 

6. The customizable kit of Widgets
   
7. Flutter has built with a rich and customizable set of widgets for Android, iOS and Material Design. The collaboration between Flutter and Google's material design has rendered and easily create a powerful User-Interface experience. This helps to create smooth, crisp and refined application experience as are available with a native application.

8. Cross-Platform
    
 With the Flutter application framework, one can build a single mobile application that will work on multiple platforms like iOS and Android. Flutter has inbuilt widget development features automatically adjust your application style components (Like button, Menu, Text, and others) based on devices that allow a user to feel like native applications.

However, flutter has associated limitations like lack of third-party libraries. Third-party libraries and packages play a big part in automating software development for programmers and relieving the need to code everything from scratch. These libraries are mostly open source and easily available.

Also, developers go to great lengths to minimize the size of an application. Users have limited storage on their phones, so it’s much more preferable to release an application that won’t make them delete it in favor of precious photos or a music library. To decrease the program size, programmers tend to avoid animations, bring the number of libraries and packages to a minimum, or compress images. Flutter has greatly frustrated developers when the release file size of the Hello world application reached 6.7MB.

##Prerequisite

In-order to learn flutter, one must have basic knowledge of dart object-oriented programming language. However, during the tutorial series, I will teach dart programming for those who are new to dart programming. Also, the dart is easy to learn for someone with object-oriented programmers' knowledge. 

##What is Dart Programming

Dart is a modern object-oriented language, if someone has knowledge in java or c++, learning dart will be easy because its syntax is more like the same. It supports both strong and weak styles making it easy to pick up for beginners. 
Both Ahead of Time and Just in Time compilation types. In development, developers usually have to opt for the compilation their programming language provides. Programs compiled Ahead-of-Time usually run faster because they’ve been compiled before. However, in this case, the development itself slows a lot. Just-in-Time compilation results in faster development cycles, but, predictably, affects the application startup speed since the compiler does it's analyzing before code execution. Flutter takes the best of both worlds by using Just in Time compilation during development and switching to Ahead of Time OT for application release. That is the advantage of using dart programming on flutter

##Flutter Installation on Linux machine

###step 1: Download flutter. 

https://storage.googleapis.com/flutter_infra/releases/stable/linux/flutter_linux_v1.12.13+hotfix.5-stable.tar.xz 

###step 2: Extract the file on the desktop or any location on your machine.

###step 3: Add flutter tool to your path

 open terminal- , copy and paste the following command.
              
        sudo nano  .bashrc
             
this command will open a text editor where you can add flutter tool to your path, scroll to the end of the file and paste the following command.


        $export PATH="$PATH:`directory where flutter is`/flutter/bin"

after pasting the command, save the file (ctrl o), press enter then type exit 

demo

![FlutterTools](https://codeswag.co.uk/wp-content/uploads/2020/01/1.Screenshot_2020-01-25_20-29-30.png  "adding_flutter_to_path")
 
NB: Do as I did on the last line of the file, make sure you replace /home/mascom/desktop 

demo if the path is correct

###step 4: Verify if the path has been added successfully.

open your terminal, copy and paste the following command
         
          flutter doctor


![demo_path](https://codeswag.co.uk/wp-content/uploads/2020/01/2.Screenshot_2020-01-25_20-47-53.png  "verifying_the_path")
**
You have successfully added flutter tool to your environment path.**

###Step 5: Downloading Command Line Tools

please click the following link to download SDK tools for Linux.

https://developer.android.com/studio/index.html#downloads

extract the zipped file on the desktop or any location on your machine.
Extracted files will be in a folder called tools 
Then we need to add SDK tools to the environment path.
Like what we did when adding flutter to the path, we do the same.
open terminal- , copy and paste the following command.
              
             sudo nano  .bashrc
             
In my case the folder tools are located in **/home/mascom/desktop**, make sure you replace with the correct path on your machine

demo

![command_line_tools](https://codeswag.co.uk/wp-content/uploads/2020/01/3.Screenshot_2020-01-25_21-02-15.png  "adding_path")
then press crtl O, press enter then type exit to save the file.


###Step 6: Verify if the path has been added successfully.

 open your terminal, copy and paste the following command
         
        sdkmanager

demo

![verify_sdk](https://codeswag.co.uk/wp-content/uploads/2020/01/4.Screenshot_2020-01-25_21-17-24.png  "sdkmanager")

You have successfully added SDK tools to your path.


##Step 7: Setting up the emulator 

open the terminal,


copy and paste 

         sdkmanager  “system-images;android-28;google_apis_playstore;x86_64"
 

after completed,

copy and paste 

         sdkmanager  “platform_tools”

after completed

copy and paste 

        sdkmanager  “build-tools;28.0.3”

after completed

copy and paste 

        sdkmanager “platforms;android-28”

after completed 

copy and paste 

        sdkmanager  “emulator”

after completed

copy and paste

        sdkmanager –licernses

usually, all these folders are installed on your desktop.

The next step we need to configure.

(1) open your terminal and type the following command.

open terminal, copy and paste the following command.
              
            $ flutter config --android-sdk /path of the android-sdk

in my case its  $ flutter config -–android-sdk
/home/mascom/Desktop/

(2) Verify if the configurations are done

 flutter for android sdk![flutter_configurations](https://codeswag.co.uk/wp-content/uploads/2020/01/5.Screenshot_2020-01-25_21-41-36.png  " flutter_for_android_sdk")

###Step 8: Setting Android_Home Path

          open the terminal on your machine

Copy and paste the following commands

          export Android_Home="/usr/lib/android-sdk/"
          export PATH="$PATH: $Android_Home/" 
            
You have installed flutter on linux machine , we are now moving to text editor set up.
 
###Step 9: Download visual code studio and install

start Visual Studio Code
Invoke View > Command Palette…. 
Type “install”, and select Extensions: Install Extensions. 
Type “flutter” in the extensions search field, select Flutter in the list, and click Install. This also installs the required Dart plugin. 

###Step 10: Creating the Application

1. Invoke View > Command Palette. 
2. Type “flutter”, and select the Flutter: New Project. 
3. Enter a project name, such as myFlutterApp, and press Enter. 
4. Create  the parent directory for the new project folder. 
5. Wait for project creation to complete and the main.dart file to appear. 
6. Invoke Debug > Start Debugging or press F5. 
Wait for the app to launch — progress is printed in the Debug Console view.

![demoApp](https://codeswag.co.uk/wp-content/uploads/2020/01/6.Screenshot_2020-01-25_22-15-15.png  "Hello_Flutter")
Ready to go with flutter on linux machine using Visual Code Studio.

##Installation of Flutter on Windows

###step 1: download flutter sdk

 https://storage.googleapis.com/flutter_infra/releases/stable/windows/flutter_windows_v1.12.13+hotfix.5-stable.zip

###step 2: Extract the zipped folder into c drive then set the environment path.

open flutter folder, open bin folder inside flutter then copy the path , add it as a variable in the system environment. See the picture below to set flutter path to environment variables.
In my case, its  **c:/flutter/bin**, copy and paste the path in the environment variable.

demo

   ![pathonwin](https://codeswag.co.uk/wp-content/uploads/2020/01/7.Screenshot_2020-01-24_15-40-32.png  "flutter_path")

###step 3:  Downloading Command Line Tools

please click the following link to download SDK tools for windows

https://developer.android.com/studio/index.html#downloads

extract the zipped file to the desktop or any location on your machine.
Extracted files will be in a folder called tools 
Then we need to add SDK tools to the environment path.

Again open the Environment variables. 
And in the System variables click on New. 
In Variable name type 

        ANDROID_HOME

Click on Browse directory and select the path to download the Android SDK:
In my case, it is 

        C:\Users\mascom\android-sdk
Now click on Ok in the 3 windows to save changes.

###  Step 6: Accept Android licenses       

  open cmd and type the following command

          flutter doctor –android-licenses 
          
 you must accept each license Press Y and Enter to accept each license 
 all android SDK will be installed by accepting the license.
              
###Step 7:  Download visual code studio and install 

Start Visual Studio Code.
Invoke View > Command Palette…. 
Type “install”, and select Extensions: Install Extensions. 
Type “flutter” in the extensions search field, select Flutter in the list, and click Install. This also installs the required Dart plugin. 

See the attached screenshots

![flutterplugin](https://codeswag.co.uk/wp-content/uploads/2020/01/7.Screenshot_2020-01-24_15-09-34.png  "Flutter_plugin")

![add_dart](https://codeswag.co.uk/wp-content/uploads/2020/01/8.Screenshot_2020-01-24_15-09-58.png "dart_plugin")

Create Flutter App using Visual Studio Code

Open command-line on vscode and paste the following command:

           flutter create myApp 

Run Flutter App on an Android Emulator from Visual Studio Code
In Visual Studio Code in the Explorer (Ctrl+Shift+E) open with double click the main.dart file that is in the folder lib (lib > main.dart). 
1. Now in the toolbar click on View > Debug > Start Debugging or F5
  and press Enter. 
2. Finally, the sample App will be executed. 

![app](https://codeswag.co.uk/wp-content/uploads/2020/01/9.Screenshot_2020-01-24_15-21-26.png "app")
