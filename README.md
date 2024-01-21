![chrome_ext](https://raw.githubusercontent.com/unixlinuxgeek/logos/main/400x400/chrome.png)

### Chrome extension development guide

A Chrome extension is composed of parts that play different roles.

#### Manifest

The extension's manifest is the only required file that must have a specific file name: manifest.json. It also has to be located in the extension's root directory. The manifest records important metadata, defines resources, declares permissions, and identifies which files to run in the background and on the page.



#### Service workers

A service workers runs in the background and handles browser events, like removing a bookmark, or closing a tab. They don't have access to the DOM, but you can combine it with an offscreen document for this use case.



#### Content scripts

Content scripts run JavaScript in the context of a web page.



#### Toolbar action

Execute code when the user clicks on the extension toolbar icon or show a popup using the Action API.



#### Side Panel

Display custom UI in the browser's side panel.

