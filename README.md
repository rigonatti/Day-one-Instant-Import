# Day-one-Instant-Import v1.0


This workflow should help to import any text, to Dayone (using DayOne2 CLI) without opening the app itself.  

## See it in Action: 
![Alfred dayone-instant-import Workflow] 
![dayone-instant-import](https://user-images.githubusercontent.com/935465/202330031-99884993-06ab-43cc-aea7-1bb1ecabc749.gif)



## Installation

* Install [DayOne CLI] (https://bit.ly/3TGsuOg)
   * You can also install DayOneCLI using: 
   ```
   	sudo bash /Applications/Day\ One.app/Contents/Resources/install_cli.sh
   ```

* Download the plugin 
* Open the workflow

> [Optional]
>      	If you have multiples Journals oon DayOne App, you can set wich Journals will be used.
>	If want to use the default Journal, leave it blank.

## USAGE: 

When typping in your favorite app like Bear, Stoic, TXT editor or any app, at the end of your entry, just type:
  
 ``` 
 :dayone
```

> Alfred asks for your Entry Title:
	-  Type your Entry Title 
	  e.g: My Journal for today

> Alfred asks for your tags:
	- type tags using espace as separator. 
		e.g: trip travelling couple

> That's it. 
  Your entry should be automatically created on DayOne using Markdown:

    # My Journal for Today
    Content Imported from your app

