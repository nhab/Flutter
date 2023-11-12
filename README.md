# Flutter

## Installation
#### Downloading
1. Search web for "Flutter" and click on Install [link](https://docs.flutter.dev/get-started/install)
2. Choose Windows
3. Scroll to "Get the Flutter SDK" and download flutter zip file form (the link is filtered in some counhteries)
4. Extract The zip into a folder like c:\SDKs

#### Set Path in Environment variable
1. click windows logo (start) and type environment , select "Edit System Environment variable" form the menu
2. Click Environment variable button in the opened dialog
3. then in system variables list select "Path" and click edit
4. Click "New" in the opened dialog, and browse for the bin folder of flutter path : c:\SDKs\Flutter\bin and ok
5. Then repeat the same process for "path" in "User variables" list

##### Testing installation
1. In Cmd , type "flutter doctor" ,It should give the information about flutter installation and what is missing

. Flutter codes can be run and tesed rapidly in the browser **without need to install Android SDK tool chain or Android Studio**

## Creating a flutter project

#### Creating a flutter project using VSCode 

1.Install Flutter ( by DartCode) Extention in vscode
2. To open command palette in VSCode: Ctrl+shift+p or Menu>View> command palette
3. Type flutter and choose new project
4. select a project type,select a Path and give a name for the project and accept to trust the created folder
5. it will generate the project 
6. In the right hand of vscode`s status bar(footer),Choose chrome instead of Windows
7. Press F5 to run the project
8. it will download needed files in first run and then runs the project.

#### Running dart file without a prject
1. close any folder and create a new file name something.dart
2. copy following dart code in it and save:
3.
```
    void main(){
       // this will print "hi"
           print("hi!");

       // variables:
           int    i= 5, j=null;
           double d= 3.14;
           string s= "what`s up?";
           var    t= 12.5;

       // using a variable inside a string:
           print("The number is $i"+d.toString());

       // "if" , "switch" ,"for",continue,break, functions,arrow functions, syntax is like c or c# language

       //class defenition:
        Class User{
            String name;
            String number;
            User   (this.name,this.number); // constructor
        }

        // class usage:
        User user1=User("Dvid","baker");
        print(user1.name);
```
4.press f5 to run it and see the result in the debug console

#### Creating flutter Project by command line
1. Type this in cmd
```
flutter create projectName
```
