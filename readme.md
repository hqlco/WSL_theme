## WSL
langkah langkah menambah tema terminal pada wsl:

### install 
```
sudo wget https://github.com/JanDeDobbeleer/oh-my-posh/releases/latest/download/posh-linux-amd64 -O /usr/local/bin/oh-my-posh
sudo chmod +x /usr/local/bin/oh-my-posh
mkdir ~/.poshthemes
wget https://github.com/JanDeDobbeleer/oh-my-posh/releases/latest/download/themes.zip -O ~/.poshthemes/themes.zip
unzip ~/.poshthemes/themes.zip -d ~/.poshthemes
chmod u+rw ~/.poshthemes/*.omp.*
rm ~/.poshthemes/themes.zip
```
### pilih tema 
```
cd ~/.poshthemes
```
### run
```
eval "$(oh-my-posh init bash --config ~/.poshthemes/(theme dipilih).omp.json)"
```
### contoh hasil

![Screenshot 2023-03-10 112923](https://user-images.githubusercontent.com/86828535/224240368-52ec607e-71c0-46e7-b689-f31d573d2230.png)

