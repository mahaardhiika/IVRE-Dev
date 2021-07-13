1. Download Geoipgen
```
wget http://morningstarsecurity.com/downloads/geoipgen-0.4.tar.gz
```
2. Extract
```
tar -xf geoipgen-0.4.tar.gz
cd geoipgen-0.4/
```
3. Download GeoIPCountryWHois.csv
```
wget https://raw.githubusercontent.com/alecthomas/geoip/master/GeoIPCountryWhois.csv
```
4. Make .geoipgen folder at home & move GeoIPCountryWhois.csv to there
```
mkdir $HOME/.geoipgen
mv GeoIPCountryWhois.csv $HOME/.geoipgen
```

5. Copy geoipgen binary to /usr/bin
```
sudo cp geoipgen /usr/bin
```

6. Instal Ruby
```
sudo apt-get install ruby
```
