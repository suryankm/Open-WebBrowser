# Open-WebBrowser
#Program to Open a web browser in python

import webbrowser
import time
print ("Opening Gulabi Movie song...." +time.ctime())
url="https://www.youtube.com/watch?v=NRlbd51Hrtg"
chrome_windows_path="C:/Program Files (x86)/Google/Chrome/Application/chrome.exe %s"
#webbrowser.open(url) ##Works with default browser.
num = 3
count = 0
while(count < num):
         time.sleep(30)
         webbrowser.get(chrome_windows_path).open(url)
         count = count + 1
