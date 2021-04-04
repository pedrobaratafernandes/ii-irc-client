# ii-irc-client
how to chat over ii irc client

more info: https://medium.com/@okubax/ii-irc-client-485a395a836a


## install ii
```
git clone https://git.suckless.org/ii
cd ii 
make
cp ii /usr/bin
```

## start ii
ii -s ptservidor.ptnet.org  -n nickname -f "i am a bot but i will reply" &

ii -s ptservidor.ptnet.org  -n nickname -f "i am a bot but i will reply" 1>output.log 2>debug.log &


### join a #channel
echo "/j #archlinux" >  ~/irc/ptservidor.ptnet.org/in

### send a message
echo "hello world" > ~/irc/ptservidor.ptnet.org/#prados_verdes/in
