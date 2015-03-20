# lightdm-webkit-ez
LightDM-webkit theme, built for your pleasure and enjoyment


#Screenshot
![alt tag](http://i.imgur.com/Q02sRYr.png)

### How to install

Instructions will differ for every platform, but I can tell you how to install it on ElementaryOS:

1. Install and enable `lightdm` and `lightdm-webkit-greeter`
2. In the terminal, navigate to `/usr/share/lightdm-webkit/themes/`
3. Clone this repository here, it should create a folder called `lightdm-webkit-ez`
4. Enable the theme in your `/etc/lightdm/lightdm-webkit-greeter.conf`
### Setting your own user picture

There are a couple of methods you can use to set your user picture in LightDM:

- Put a `jpg` of your face in your home directory as a file called `.face`

or

- Add `Icon=/path/to/your/face.png` to the bottom of `/var/lib/AccountsService/users/<youraccountname>`

