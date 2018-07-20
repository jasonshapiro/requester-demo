# Rapid API Testing and Development with Requester

[**Requester**](http://requester.org/) is a HTTP client plugin for **Sublime Text 3** - a feature-rich, extensible text editor with a well-maintained, **active plugin ecosystem**. If you don't have ST3 already, you can download it [here.](https://www.sublimetext.com/)


### Setting up Sublime

After installation, make sure you are connected to the clear-guest network. Then open Sublime from your Applications folder. 

Press `cmd + shift + p` to open the command palette and select the option to install Package Control.

Press `cmd + shift + p` again and select Package Control: Install Package. Then search for the **Requester** plugin. Select it and press enter.

--

### Using Requester

For reference, here is the [Requester API](http://requester.org/)

The most simple usage of requestor is running a quick HTTP GET request by selecting a URL and pressing `ctrl + r`. The subsequent response is opened in a new window.

More advanced HTTP requests can be formed using the very readable [requests](http://docs.python-requests.org/en/master/user/quickstart/) syntax. 