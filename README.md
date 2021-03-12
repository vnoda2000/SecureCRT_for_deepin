# 安装SecureCrt 8.5.4到deepin 20.1



SecureCrt需要依赖libssl1.0.0,而deepin里默认自带的是libssl1.1.1版本，版本过高导致不兼容，因此直接下载libssl1.0.0的deb包使用`dpkg -i`安装即可。
另外SecureCrt还依赖libpng12,同样下载deb包解决

## libssl1.0.0的下载地址
`https://pkgs.org/download/libssl1.0.0`

## libpng12的下载地址
`https://pkgs.org/search/?q=libpng12`

选Ubuntu 16.04 LTS里的`libpng12-0_1.2.54-1ubuntu1_amd64.deb`下载即可

