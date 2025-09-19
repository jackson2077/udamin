# udamin.github.io

### 文件命名和域名替换规则

1. 以字母命名的目录下，都放着以该字母开头命令的文件，文字名的最后一位数字代理着他的位置，如a目录下的autocomplete-4h88d7nptsah2.html，他的文件名最后一个数字为2，那说明他是其实是第二个文件
2. 在文件里，String.fromCharCode里的charCode，是由"https://xg1.aabbcc.dd?token="这样的url转换过来的
3. 一个目录下里的文件都只对应一个域名，但是对应的是不同的二级域名，如以数字1结尾的对应的域名是xg1.aabbcc.dd，数字2对应的是xg2.aabbcc.dd，数字3对应的是rb.aabbcc.dd，数字4对应的是cdn.aabbcc.dd,数字5对应的是cf.aabbcc.dd
4. 域名的首字母和目录名一致
5. 替换域名时，只替换主域名部分，如xg1.aabbcc.dd，只替换主域名aabbcc.dd