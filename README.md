# Miner-Ubuntu
  
wget https://github.com/Lolliedieb/lolMiner-releases/releases/download/1.73/lolMiner_v1.73_Lin64.tar.gz  
  
edit miner_kas.sh >>  
1. add "sleep 10" first line for delay before start  
2. wallet-pool id from >> https://www.mexc.com/login?previous=%2Fassets%2Fdeposit%2FKAS >>   kaspa:qpg6cy8gyf3ncewkpansuh75xhtm9tmy4pu4emjkh6hcqc5d2yy2w3rvlgljh.rig3
3. Check pool >> https://kaspa.herominers.com/
4. Check wallet >> https://www.mexc.com/login?previous=%2Fassets%2Fdeposit%2FKAS

crontab -e  
SHELL=/bin/sh  
HOME=/home/phawit/Documents/Miner/1.73  
@reboot bash miner_kas.sh >> /home/phawit/Documents/Miner/run.log  


