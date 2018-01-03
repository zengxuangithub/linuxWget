#  wget命令

 -  -o 参数 
  
```
wget -o test.zip  http:www.test.com/xxx.zip
//将所下载的文件以test.zip 命名保存   
// 默认是以最后一个'/'后面的字符命名  此处为xxx.zip
```

-  -P参数(大写P) 

(暂时不知道为啥不能和-o参数同时使用)
```
wget -P  ./test http:test.com/xxx.zip
//下载到当前目录下 的test文件夹里面 
//如果test文件夹不存在  则创建test文件夹
```

