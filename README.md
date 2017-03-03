# Tabchi V4

اموزش ران کردن ربات تب جی
اول کد های زیر رو جدا جدا بفرستید


```
sudo apt-get update
sudo apt-get upgrade
```
بعدش
```
sudo apt-get install libreadline-dev libconfig-dev libssl-dev lua5.2 liblua5.2-dev lua-socket lua-sec lua-expat libevent-dev make unzip git redis-server autoconf g++ libjansson-dev libpython-dev expat libexpat1-dev ppa-purge python3-pip python3-dev
```
و حالا باید ببینید ورژن سرورتون چنده

```
lsb_release -a
```
گه متن زیر اومد قسمت (اول) رو انجام ندید
Distributor ID: Ubuntu                                                                        
Description:    Ubuntu 16.04.1 LTS                                                            
Release:        16.04                                                                         
Codename:       xenial

## قسمت اول
کد های زیر رو دونه دونه بفرستید و هرجا لازم بودy بفرستید یا اینتر

```
sudo apt-get install update-manager-core
sudo do-release-upgrade
```
بعد برای اینکه ببینید اپدیت شد یا نه دستور زیر رو بفرستید
```
lsb_release -a 
```
## قسمت دوم
حال باید سورس رو کلون کنید

```
git clone https://github.com/punisherteam/Tabchi
cd Tabchi
chmod 777 install.sh
./install.sh
```
بعدش

```
lua creator.lua
```

بعد ازتون ایدی عددی ربات 
بعد ایدی عددی خودتون
بعدش یه متنی میاد مثل زیر

./tabchi-//////////.sh

اینو کپی پیست کنید و بعد ازتون شماره و بعد کدو میخواد 


## Run
Use `./tabchi-ID.sh` to run your bot normaly or use `screen ./tabchi-ID.sh` for auto launch mode (put tabchi-id in ID part)

## Run all bots
Use `tmux new-session -s tabchi-anticrash "bash anticrash.sh"` to run all bots

## Help and more...
Send `/start` to [@TabChiRobot](https://telegram.me/TabChiRobot) in telegram


برای فهمیدن ایدی عددی خود به
` @userinfobot` 
پیام بدهید
 
 ## Developers
 * [mamadkiller](https://telegram.me/Bmamadkiller)
 
