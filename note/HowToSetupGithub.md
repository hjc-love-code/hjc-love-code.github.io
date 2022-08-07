# How to setup Github

- Step 1  
    install git
- Step 2 (setup git)  
    ```cmd
    git config --global user.name "Your Name"
	git config --global user.email "email@example.com"
	git config --global http.proxy socks5://127.0.0.1:1081
    git config --global https.proxy socks5://127.0.0.1:10817/10/2022 
    ```
- Step 3 (setup github and system)  
	- Open github => setting => Developer Settings => Personal Access Token => Generate New Token (Give your password) => Fill up the form => click Generate token => Copy the generated Token 
	to notepad. 

	- Open `Windows Credentials Manager` => find git:https://github.com => Edit => On Password replace with  your GitHub Personal Access Token 

- Step 4 (push code)  
	- Open github and clone the repository and enter in command line:
        ```cmd
        git clone (Your repository address)
        git add .
        git commit -m "Your comments"
        git push origin main
        ```
