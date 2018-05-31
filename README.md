

## IRC

* Open a seperate browser
* Login to IRC: [https://kiwiirc.com/client](https://kiwiirc.com/client)
* Use your username
* set `#ce888` for the channel name
* Type some random stuff once you are in
	


<!-- 
## Configuring the VM with extra packages



* Extra package installation
	* `sudo apt-get install enchant`
	

* Install NLTK - THIS IS ALLREADY DONE, DON'T DO IT
  *  `sudo pip install sopel`
  * ```sudo pip install nltk```
  * ```sudo python -m nltk.downloader -d /usr/local/share/nltk_data punkt```
  * ```sudo python -m nltk.downloader -d /usr/local/share/nltk_data wordnet```
  * ```sudo python -m nltk.downloader -d /usr/local/share/nltk_data averaged_perceptron_tagger```

 -->
## Running a Sopel bot

Type `sopel` AND ENTER YOUR OWN NICKNAME+bot as nickname
>    I can't seem to find the configuration file, so let's generate it!
>
>    Please answer the following questions to create your configuration file:
>
>
>    Enter the nickname for your bot. [Sopel] ssamotbot
>
>    Enter the server to connect to. [irc.dftba.net] irc.freenode.net
>
>    Should the bot connect with SSL? (y/n) [n] y
>
>    Enter the port to connect on. [6697]
>
>    Enter your own IRC name (or that of the bot's owner) ssamotbot
>
>    Enter the channels to connect to at startup, separated by commas. []
>
>    ? #ce888
>
>    ?
>
>    Would you like to see if there are any modules that need configuring (y/n)? [n]
>
>    Config file written sucessfully!


* Once you have reached this point, press ctrl+c to exit (once the bot is connected)
* Configure sopel modules to point the current directory
	* `cd .sopel`
	* `nano default.cfg`
	* add to the end `extra = .`
	* Save and exit 


## Bringing the labs from github
* Got your home directory (i.e. /home/mlvm2)
* Do `git clone https://github.com/ssamot/ce888.git`
* Copy ce888/labs/lab1 into your local github lab directory
	* That would be something like ce888labs/lab1
	* Obviously create the directory if it doesn't exist 

