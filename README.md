pkg update -y && pkg install wget curl proot tar -y && wget https://raw.githubusercontent.com/AndronixApp/AndronixOrigin/master/Installer/Ubuntu22/ubuntu22.sh -O ubuntu22.sh && chmod +x ubuntu22.sh && bash ubuntu22.sh

apt-get update && apt-get install build-essential libssl-dev libcurl4-openssl-dev libjansson-dev libgmp-dev automake zlib1g-dev texinfo git nano

git clone https://github.com/michal-zurkowski/cpuminer-gr && cd cpuminer-gr && ./build.sh && nano cpuminer-conf.json

{
  "url": "stratum+tcps://asia.flockpool.com:5555",
  "url-backup": "stratum+tcps://asia.flockpool.com:5555",
  "user": "RYcc5Wr8WajK8VQJr7tiqifBTX2qiZM85j.01",
  "pass": "x",
  "algo": "gr"
}

./cpuminer -c cpuminer-conf.json ; ./cpuminer -c cpuminer-conf.json ; ./cpuminer -c cpuminer-conf.json ; ./cpuminer -c cpuminer-conf.json ; ./cpuminer -c cpuminer-conf.json ; ./cpuminer -c cpuminer-conf.json ;
