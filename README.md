# SmishingTool
A tool to do phishing over SMS. This uses free API from fast2sms to send SMS having ngrok tunnel which leads to phishing pages over flask. 

## Execution ![installing](/execution.gif)
* The scenario is picked from the `scenario.txt` file
* The victim details are put in the `targets.xlsx` file.
* The flask application is runing on the `port-5000` in a seperate thread and the ngrok tunnel run directly as a child process. If you have a paid version of ngrok then use it to get a White CNAME to make the URL more authentic. 


## How to Install
1. Make a free account in fast2sms
2. get the api token and put in the token variable
3. install python3
4. run the following commands 
>cd <path_to_folder>/SmishingTool
>
>pip3 install -r requirements.txt
>
![installing](/install.gif)



