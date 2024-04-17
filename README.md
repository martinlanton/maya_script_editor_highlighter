This plugin lets you easily see errors and warnings in the Maya console.  
![image](https://github.com/hannesdelbeke/maya_script_editor_highlighter/assets/3758308/4f15a866-1d87-45a5-9cf6-e779a4bf17ee)  
it's quite primitive, e.g. the line `// https://www.autodesk.com/maya-arnold-not-available-error` will be colored as an error  

### install
* Copy the `script_editor_highlighter.py` in your plugins folder `%UserProfile%\Documents\Maya\plug-ins` OR
* Edit your environment variables to add the plug-in folder to your list of plugin locations. This can be done by adding the location of the plug-ins folder location (for example `C:\Users\JohnDoe\Documents\maya_script_editor_highlighter\src\plug-ins`, or wherever you decided to put it) to the `MAYA_PLUG_IN_PATH` environment variable.

#### Alternatively, you can use the userSetup.py version
* Add the `script` folder location (for example `C:\Users\JohnDoe\Documents\maya_script_editor_highlighter\src\scripts`, or wherever you decided to put it) to the `PYTHONPATH` environment variable.

### Usage
1. Enable the highlight plugin (if you chose the plug-in version)
2. Open script editor.
3. It won't work until you get focus on the script editor, this means you'll need to activate focus on a different part of the GUI, then back on the script editor. To do this, simply click on the viewport then back on the script editor.


### reference
see https://hannesdelbeke.github.io/wiki/tech%20art/maya/Maya%20script%20editor%20syntax%20highlight/
