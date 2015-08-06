#Installation of Owncloud on CentOS 

<ol>
  <b><li>Installing CentOS 7 on virtual box</li><b>
</ol>

![Alt text](http://i58.tinypic.com/2cmnm95.jpg)

![Alt text](http://i59.tinypic.com/nc08ly.jpg)

![Alt text](http://i58.tinypic.com/2a8osnm.jpg)

![Alt text](http://i60.tinypic.com/2nlfec1.jpg)

![Alt text](http://i58.tinypic.com/2zibvkn.jpg)

![Alt text](http://i60.tinypic.com/20t0xuc.jpg)

![Alt text](http://i59.tinypic.com/w8l112.jpg)

![Alt text](http://i62.tinypic.com/2q36p9k.jpg)

![Alt text](http://i62.tinypic.com/2mfb4sj.jpg)

![Alt text](http://i57.tinypic.com/2r451c4.jpg)

![Alt text](http://i58.tinypic.com/vhz2ip.jpg)

![Alt text](http://i59.tinypic.com/15rhb1s.jpg)

![Alt text](http://i62.tinypic.com/erx0l5.jpg)

![Alt text](http://i61.tinypic.com/1zb7yx3.jpg)

![Alt text](http://i59.tinypic.com/eh189x.jpg)

![Alt text](http://i59.tinypic.com/rlm1cl.jpg)

<ol start = "2">
  <b><li>CentOS 7 running on virtual box</li><b>
</ol>

![Alt text](http://i62.tinypic.com/14y09as.jpg)

![Alt text](http://i62.tinypic.com/2hs7jww.jpg)

![Alt text](http://i61.tinypic.com/6seyc9.jpg)

![Alt text](http://i60.tinypic.com/xm4oz7.jpg)

<ol start = "3">
  <b><li>Update CenOS 7</li><b>
</ol>

![Alt text](https://raw.githubusercontent.com/gayumidecosta/ESBII/master/Sentos/lab5/21.JPG)

<ol start = "4">
  <b><li>Install PHP, Apache web server and MySQL server and some php extensions</li><b>
</ol>

![Alt text](https://raw.githubusercontent.com/gayumidecosta/ESBII/master/Sentos/lab5/22.JPG)

![Alt text](https://raw.githubusercontent.com/gayumidecosta/ESBII/master/Sentos/lab5/23.JPG)

![Alt text](https://raw.githubusercontent.com/gayumidecosta/ESBII/master/Sentos/lab5/24.JPG)

![Alt text](https://raw.githubusercontent.com/gayumidecosta/ESBII/master/Sentos/lab5/25.JPG)

<ol start = "5">
  <b><li>Set SELinux to allow OwnCloud to write the data</li><b>
</ol>

![Alt text](https://raw.githubusercontent.com/gayumidecosta/ESBII/master/Sentos/lab5/26.JPG)

<ol start = "6">
  <b><li>Allow web traffic through the firewall</li><b>
</ol>

![Alt text](https://raw.githubusercontent.com/gayumidecosta/ESBII/master/Sentos/lab5/27.JPG)

<ol start = "7">
  <b><li>Start Apache</li><b>
</ol>

![Alt text](https://raw.githubusercontent.com/gayumidecosta/ESBII/master/Sentos/lab5/28.JPG)


<ol start = "8">
  <b><li>Start  MariaDB</li><b>
</ol>

![Alt text](https://raw.githubusercontent.com/gayumidecosta/ESBII/master/Sentos/lab5/29.JPG)

<ol start = "9">
  <b><li>Auto start the service at system start-up</li><b>
</ol>

![Alt text](https://raw.githubusercontent.com/gayumidecosta/ESBII/master/Sentos/lab5/30.JPG)

<ol start = "10">
  <b><li>Download ownCloud from official website and extract the archive we just downloaded</li><b>
</ol>

![Alt text](https://raw.githubusercontent.com/gayumidecosta/ESBII/master/Sentos/lab5/31.JPG)

![Alt text](https://raw.githubusercontent.com/gayumidecosta/ESBII/master/Sentos/lab5/32.JPG)

<ol start = "11">
  <b><li>Assign the permission for web server to read and write the files on cloud directory</li><b>
</ol>

![Alt text](https://raw.githubusercontent.com/gayumidecosta/ESBII/master/Sentos/lab5/33.JPG)

<ol start = "12">
  <b><li>Configure the mariadb instance</li><b>
</ol>

![Alt text](https://raw.githubusercontent.com/gayumidecosta/ESBII/master/Sentos/lab5/34.JPG)

![Alt text](https://raw.githubusercontent.com/gayumidecosta/ESBII/master/Sentos/lab5/35.JPG)

<ol start = "13">
  <b><li>Login to mysql server</li><b>
</ol>

![Alt text](https://raw.githubusercontent.com/gayumidecosta/ESBII/master/Sentos/lab5/36.JPG)

<ol start = "14">
  <b><li>Open an external configuration file for ownCloud in your favorite editor, I’m using vim</li><b>
</ol>

![Alt text](https://raw.githubusercontent.com/gayumidecosta/ESBII/master/Sentos/lab5/37.JPG)

<ol start = "15">
  <b><li>Add the following lines in the config file</li><b>
</ol>

![Alt text](https://raw.githubusercontent.com/gayumidecosta/ESBII/master/Sentos/lab5/38.JPG)

<ol start = "16">
  <b><li>Restart all apache and mariaDB services</li><b>
</ol>

![Alt text](https://raw.githubusercontent.com/gayumidecosta/ESBII/master/Sentos/lab5/39.JPG)

<ol start = "17">
  <b><li>OwnCloud configuration</li><b>
</ol>

![Alt text](https://raw.githubusercontent.com/gayumidecosta/ESBII/master/Sentos/lab5/40.JPG)

![Alt text](https://raw.githubusercontent.com/gayumidecosta/ESBII/master/Sentos/lab5/41.JPG)

![Alt text](https://raw.githubusercontent.com/gayumidecosta/ESBII/master/Sentos/lab5/42.JPG)
