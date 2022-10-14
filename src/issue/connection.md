# Git

解决git下载报错: fatal：unable to access 'https://github.com/...':

1、在git中执行
git config --global --unset http.proxy
git config --global --unset https.proxy

2、在cmd下执行
ipconfig/flushdns 清理DNS缓存

3、重新执行git clone https://github.com/… 即可
