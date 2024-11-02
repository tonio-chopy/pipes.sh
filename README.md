# pipes.sh
pipes.sh script to execute.

curl -O https://raw.githubusercontent.com/pipeseroni/pipes.sh/master/pipes.sh

chmod +x pipes.sh

mkdir -p ~/bin

mv pipes.sh ~/bin/

echo 'export PATH="$HOME/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc
