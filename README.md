# HistorySniffing2023
Stealing Browser History Through Side Channels

## Requirements
To validate the experiments, we ran them on a Lenovo ThinkPad P14s Gen 1 laptop equipped with an Intel Core i7-10610U CPU clocked at 1.80GHz. We used Google Chrome version 109.0 as the browser and Microsoft Windows 11 Pro as the operating system. The laptop was connected to a power source throughout the experiments to ensure consistent performance.

In addition, we used Python 3 to run the HTTP server for serving the attack pages.

## Steps
1. Delete Chrome history
2. Open urls.html in Chrome and visit all urls in the visited list
1. Open the command line and run "python cors_web_server.py"
2. Load each of the attack pages in Chrome browser at localhost:8000
