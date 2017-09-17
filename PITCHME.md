# ManicTimeにlinux版がリリースされたので使ってみたテスト  

2017/09/18  

---

## 自己紹介  
* 県大に2007に編入(石亀研)  
* 2009に大学院進学  
* なんやかんやで2012くらいに辞めました  
* なんやかんやで2014くらいにSターン就職  
* 会社ではweb系の仕事をしています  
* 最近舌打ちとため息が増えました  

---

## ManicTimeって？  
* あなたが何時何のアプリケーションをアクティブで使用していたか延々と記録します  
* 使用状況を遡って確認することが出来ます  

![](https://github.com/kusuke82/ioc16_1/images/ManicTime-Client.png)  

---

## 私とManicTime  
* 使用履歴7〜8年(うろおぼえ)  
* Windowsでずっと使ってました  
* 主に自分の生活サイクル確認  

---

今回はManicTimeにlinux版が出たので使ってみます  

---

## インストール  
* ubuntu16.04  
* mono 4.8  

```sh
sudo apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv-keys 3FA7E0328081BFF6A14DA29AA6A19B38D3D831EF
echo "deb http://download.mono-project.com/repo/ubuntu xenial main" | sudo tee /etc/apt/sources.list.d/mono-official.list
sudo aptitude update
sudo aptitude install mono-devel
```

---

今はここまで  


---










