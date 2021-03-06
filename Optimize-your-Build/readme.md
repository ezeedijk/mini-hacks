![Xpirit TechDays MiniHack Banner](../HackBanner-s.png)
# Optimize & Enhance your Build #

## Challenge ##
In this mini-hack you will learn several optimization & enhancements to your build defintion. These features can help you keep your build and output quick en lean.

## Prerequisites ##
To get started with this mini-hack, you will need the following 

- Create a Microsoft Account (e.g. Outlook.com)
- Create a GitHub account
    - Navigate to https://github.com and signup for a new account
    - Verify your GitHub account via emails
- Create a Visual Studio Team Systems (VSTS) account
    - Signup for a free VSTS account here https://www.visualstudio.com/

## The Assignment ##

### Step 1 - Edit the Build Definition ###

Edit your build definition, and choose to make ik a Multi-Configuration Build.
Specify the following Multipliers: **BuildConfiguration, BuildPlatform**
Choose to let then run in parallel.

Specify the following BuildConfigurations to build: **Debug,Release**

Build and verify the build uses multiple configurations.

### Step 2 - Manage Multiple Artifacts ###

Since we have multiple configurations, lets make sure we get the output seperatly dropped
Update the Publish Artifacts step and specify the following Artifact Name: **DLL - $(BuildConfiguration)** 

Run a build and verify in the succesfull build artifacts that you now have multiple outputs.

## Finished! ##
You have succesfully finished this Mini-Hack! Please notify a Mini-Hack host show them the following result(s);

- Show the build artifact explorer contiaining multiple artifact sources

After validation by the host you can use the TechDays 16 app to unlock the a Mini-Hack specific badge!

If you do not have the TechDays 16 App yet be sure to download it;
- iOS <https://xpir.it/td16-ios>
- Android <https://xpir.it/td16-droid>
- Windows Phone <https://xpir.it/td16-win>