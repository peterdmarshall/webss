# webss

### Clone the repo
Navigate to your bin\
```cd /bin```

Clone the repo\
```git clone git@github.com:peterdmarshall/webss.git```

Add the folder to your path by adding the following line to the end of ```~/.bashrc```\
```export PATH=$PATH:/bin/webss```

Make the script executable\
```cd webss```  
```chmod u+x webss```

### Get an Imgur clientid
[Make an Imgur account](https://imgur.com/register) if you do not already have one.
Register your application [with the imgur api](https://api.imgur.com/oauth2/addclient)

Copy the generated client ID and paste it into ```/bin/webss/webss.conf```
```CLIENT_ID=YOUR_CLIENT_ID_HERE```

### Run webss
Open a new shell and run ```webss```. Your clipboard should now have a link to the hosted Imgur image.

### Bind to a keyboard shortcut
