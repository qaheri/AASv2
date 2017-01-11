**source by *@mrMT5* **
```
# روش اول
cd $HOME
git clone https://github.com/qaheri/AASv2.git
cd AASv2
chmod +x launch.sh
./launch.sh install
./launch.sh # Enter a phone number & confirmation code.
```
#روش دوم 
#(ترجیها)
```
sudo apt-get install git && git clone https://github.com/qaheri/AASv2.git && cd AASv2 && chmod +x launch.sh && ./launch.sh install && ./launch.sh
```
# Auto Launch Bot With :
```
killall screen
killall tmux
killall telegram-cli
tmux new-session -s script "bash steady.sh -t"
```

# Auto Launch Confiure :

**go to steady.sh and config it !**

***Then Go To line 9 - 10 and change bot folder name and reload time!***
