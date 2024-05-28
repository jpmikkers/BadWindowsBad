# Bad Windows, bad!
Collection of fixes for things I find annoying about Windows 11

## Start menu microsoft account nagging

<img src="./Screens/accountnag.jpg" width="50%" height="50%">

To disable this, in group policy editor (gpedit), navigate to:

    User Configuration > Administrative Templates > Windows Components > Account Notifications

then enable the setting:

    Turn off account notifications in start
    
## Start menu web search
To disable this, in group policy editor (gpedit), navigate to:

    Computer Configuration > Administrative Templates > Windows Components > Search

then enable the settings:

    Do not allow web search

and:

    Don't search the web or display web results in Search
    
