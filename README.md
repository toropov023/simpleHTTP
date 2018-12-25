# simpleHTTP
Open a simple HTTP handler with password protection and upload functionality

Based on:
</br>
https://gist.github.com/Siedlerchr/fb74927d822fd9408f34d8386cc05b5a
https://github.com/tianhuil/SimpleHTTPAuthServer/blob/master/SimpleHTTPAuthServer/__main__.py

Requires Python 3

Sample usage with tmux:
</br>
<code>
tmux attach -t sessionHTTP || tmux new-session -s sessionHTTP './openServer.sh username password'
</code>
