# onebox-venueconfig-api

## API to get all the venue configurations from any external ticketing system.

To do so, we have used a **API Blueprint** standard, **apiary** as an online editing and mocking tool, **aglio** to document it, **getsandbox** as a sandbox provider, **atom** as local editor and **mockapi** as a local sandbox.
+ [API Blueprint](https://apiblueprint.org/)
+ [apiary.io](http://docs.oneboxvenueconfigapi.apiary.io/)
+ [getsandbox.com](http://onebox-venueconfig-api.getsandbox.com/)
+ [aglio](https://github.com/danielgtaylor/aglio)
+ [atom](http://atom.io)
+ [mockapi](https://github.com/joliva-ob/mockapi)
+ [github](https://github.com/joliva-ob/onebox-venueconfig-api)
+ [onebox-developer](http://developer.oneboxtickets.com/venueconfig-api/index.html)

### Usage
1 edit the api blueprint document with apiary.io, or edit directly with Atom + blueprint plugin preview, language and lintr validation. This will provide a **.md** or **.apib** file.

2 generate the documentation from the .apib file with aglio from the command line:
```
aglio -i apiary.apib -o index.html
```
3 update the online mock service by singin at https://getsandbox.com, going to onebox-crm-api and re-importing source from the .apib file. Or start mockapi from command line. And finally, mock will be available for testing at: http://onebox-venueconfig-api.getsandbox.com/{uri_path}, ie: /api/v1.0/users from any browser, postman or soapui.

4 Apiary.io is already connected with github, so should be already up to date.
