#Downloading python, pip, and tweepy:

Download latest v of python
https://www.python.org/downloads/

pip should already be installed if not, paste in terminal:
curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py

then run
python get-pip.py

then run
pip install tweepy

#Bot stuff:

Create a twitter dev account
Create an application.
Apps>your_app_name> keys and tokens

in a text editor
1.	Create a folder called twitter bot
2.	Create a file called config.py
3.	Copy paste the config.py file
4.	Put in your keys and tokens
5.	Create a new file called test.txt and write whatever you’d like in it
6.	Create a new file called tweet-from-file.py
7.	Copy paste the tweet-from-file.py file
8.	In terminal cd into your folder
9.	Run python3 tweet-from-file.py
10.	You should see your file printed in the terminal and tweeted to your bot

Look at the github repos below to learn how to use for loops and the sleep function to continuously tweet.

#Tweepy API documentation
http://docs.tweepy.org/en/latest/getting_started.html#api

#Referenced repos
https://github.com/sarrasou/simple_tweepy_tut

https://github.com/y-mehta/twitter-bot
