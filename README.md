# VsCode-Settings

### Contents
- [VsCode-Settings](#vscode-settings)
    - [Contents](#contents)
  - [Welcome](#welcome)
    - [My VS Code use case and history](#my-vs-code-use-case-and-history)
  - [Extensions](#extensions)
    - [Markdown and writing](#markdown-and-writing)
      - [Markdown all in 1](#markdown-all-in-1)
      - [LtX](#ltx)
    - [Collaboration](#collaboration)
      - [Live share extension pack](#live-share-extension-pack)
    - [Python](#python)
      - [Python](#python-1)
    - [Web development](#web-development)
      - [Live server](#live-server)
  - [Keyboard shortcuts](#keyboard-shortcuts)
    - [Live Share:](#live-share)
    - [Notifications:](#notifications)
    - [getting my settings](#getting-my-settings)
      - [Downloading settings sync extension](#downloading-settings-sync-extension)
      - [Settings sync setup](#settings-sync-setup)

## Welcome
Welcome to my VS Code settings repo. Here you can learn about the different settings and configurations I like to use for VS Code and get them for yourself. I will also give some explanation on why I like certain settings and extensions.

### My VS Code use case and history
I started to use VS Code the first day I knew about it and have used exclusively for the past 2 years. Over this time, my usage has expanded from just writing code in the beginning and now doing crazy things like managing the entire git process and even collaborating with colleegs using an extension called liveshare. The early days for accessibility were interesting and filled with many bugs but thanks to Microsoft's commitment to accessibility and the open-source community, it is the best editor for those who rely on screen readers. Today, I use VS Code for all sorts of things ranging from writing this documentation, writing, and running python, running a live web server, and so much more. The nice thing is that it is so simple but can be expanded thanks to the amazing extension library present.

## Extensions 
These help extend the functionality of VS Code and sometimes even add new functionality. Below, I will go into detail about the extensions I use.

### Markdown and writing
I write markdown daily. In fact, I am writing markdown as we speak for this documentation. I like it because of the simplicity and the accessibility. While Markdown is easy to write, I use the following extensions to help me write better Markdown and ensure it is readable.

#### Markdown all in 1
This extension is amazing! Everything to do with Markdown is included from basic headings to complex math rendering using LaTeX and math ml. This extension is what is allowing me to generate the table of contents and preview my work to the side of the editor.

#### LtX
LTX is an extension that checks your spelling and grammar within VS Code. I love this extension because I do not need to leave VS Code for spelling and grammar checking. I write tuns of documentation so not needing to leave VS Code is nice and saves me time.

### Collaboration
There are many times when I collaborate with other people. In my case, I use this for my classes that I teach or working with a team on code.

#### Live share extension pack
Threw VS Code, you can collaborate with others using a group of extensions called liveshare extension pack made by microsoft. How it works is you log in with your GitHub or Microsoft, and you could get an invitation by others or host a session and invite threw links or direct invites. You can use this for classes, work, or whatever you want. Code is shared along with terminals, but you cannot have all participants run the code because you are working off the host's computer. In addition, you can also call the participants directly threw liveshare, but I personally have not tried this feature. Finally, you can chat with the participants in the sessions. This is an amazing extension and would highly recommend.

### Python
Another part of my work is writing lots of code. I write code in many languages, but python is my main one.

#### Python
The python extension is the best extension for python. This extension allows VS Code to act as a python editor. This is a must for writing python code.

### Web development

#### Live server
This is an extension that can render static webpages in a browser. When you save the file, the server updates in real-time and can even be shared threw liveshare. These extensions save me time because I do not need to constantly press f5 to refresh.

## Keyboard shortcuts
I modified the following keyboard shortcuts for ease of use.

###Terminal Commands:
Toggle Integrated Terminal - CTRL + T
Next Terminal - Alt + N
Previous Terminal - Alt + P
Kill Active Terminal - CTRL + Shift + K

### Live Share:
Focus Terminal - CTRL + Shift + F T
Focus Contacts - CTRL + Shift + L I

### Notifications:
Show Notifications - CTRL + K N

### getting my settings
If these extensions and configurations sound apealing and you want to use them, you need to go threw a few steps.

#### Downloading settings sync extension
1. Open your VS Code editor.
2. Press Ctrl+shift+x to locate the extensions. You should land in a search field.
3. Type settings sync and press tab to locate the list of extensions.
4. You can now use your arrows to navigate the list of extensions. You want to select the first option.
5. Tab until you here install. This should be the first thing you come across.
6. Wait until the extension is installed and reload by pressing alt+f4.

#### Settings sync setup
when you first return to VS Code, you will see a welcome page for settings sync. We will find the link that says download public gist and enter the folllowing id excluding the quotes "0e89115e50534c3f3f57e94875ff7fa9". From this point, you should be installing the settings. You will need to reload to activate. Finally, you should be all set to go.