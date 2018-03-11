# BrowserSettingAPI Documentation
Designed and created using C#. 

# Class Hierarchy

![screenshot 160](https://user-images.githubusercontent.com/22167688/37251772-2a8416f4-253c-11e8-94b7-e69d7e726ab5.png)

# Usage
* Add the file as an reference to your C# project using Solution Explorer.
1. In Solution Explorer.
2. Right Click References.
3. Add Reference.
4. Browse for the file name **BrowserSettings.dll.**
5. Click OK.

*  Create an object of Class BrowserRegistrySettings and pass Web browser object into the BrowserRegistrySettings constructor.
Example: 
```C#
using System;
using System.Windows.Forms;
        |
        |
        |
        |
 using BrowserSettings;    //  API Namespace        

class MyProject
{
    WebBrowser myBrowser = new WebBrowser();

  BrowserRegistrySettings  obj = new BrowserRegistrySettings(myBrowser);  // That's it to use the API
         |
         |
         |
         |
  
}
```
