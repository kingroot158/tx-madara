####install go####  <br />
wget -c https://go.dev/dl/go1.22.0.linux-amd64.tar.gz <br />
tar -C /usr/local/ -xzf go1.22.0.linux-amd64.tar.gz <br />
export PATH=$PATH:/usr/local/go/bin <br />
go version <br />

--------------------------------------------------------------  <br />
###run tx madara###
git clone https://github.com/andremax/tx-madara.git <br />
cd tx-madara <br />
nano rpc.json ( replace url di rpc.json ) <br />
go mod tidy <br />
screen -S tx <br />
go run main.go <br />
ctrl a+d (min screen) <br />
----------------
screen -ls (look screen) <br />
screen -x idxxxx (masuk screen)
