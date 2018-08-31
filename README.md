# geth-hack
Geth Port Scanner and Save - Geth Hacking

##### First install masscan
centos 
yum install masscan
ubuntu
sudo apt-get install masscan
##### first scan 8545 port masscan
sh masscan.sh
##### scan finish and start.py
python start.py
The success.txt file shows you successful results.
###### if it finds a file for you. After that, it's your talent.


# Other Option
```
r = requests.get('https://www.ethernodes.org/network/1/data?draw=1&columns[0][data]=id&columns[0][name]=&columns[0][searchable]=true&columns[0][orderable]=true&columns[0][search][value]=&columns[0][search][regex]=false&columns[1][data]=host&columns[1][name]=&columns[1][searchable]=true&columns[1][orderable]=true&columns[1][search][value]=&columns[1][search][regex]=false&columns[2][data]=port&columns[2][name]=&columns[2][searchable]=true&columns[2][orderable]=true&columns[2][search][value]=&columns[2][search][regex]=false&columns[3][data]=country&columns[3][name]=&columns[3][searchable]=true&columns[3][orderable]=true&columns[3][search][value]=&columns[3][search][regex]=false&columns[4][data]=clientId&columns[4][name]=&columns[4][searchable]=true&columns[4][orderable]=true&columns[4][search][value]=&columns[4][search][regex]=false&columns[5][data]=client&columns[5][name]=&columns[5][searchable]=true&columns[5][orderable]=true&columns[5][search][value]=&columns[5][search][regex]=false&columns[6][data]=clientVersion&columns[6][name]=&columns[6][searchable]=true&columns[6][orderable]=true&columns[6][search][value]=&columns[6][search][regex]=false&columns[7][data]=os&columns[7][name]=&columns[7][searchable]=true&columns[7][orderable]=true&columns[7][search][value]=&columns[7][search][regex]=false&columns[8][data]=lastUpdate&columns[8][name]=&columns[8][searchable]=true&columns[8][orderable]=true&columns[8][search][value]=&columns[8][search][regex]=false&order[0][column]=8&order[0][dir]=desc&start=0&length=30000&search[value]=&search[regex]=false&_=1517230965098')
	data = r.json()["data"]
	for val in data:
		host = val["host"]
		clientId = val["clientId"]
		port = val["port"]
```
## Donate ETH : 0xC6c42a825555fbef74D21B3Cb6bFd7074325C348 Thank you!
