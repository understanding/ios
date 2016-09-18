# ios
http://blog.csdn.net/foreverdiy/article/details/47417369
提示：大家会想，plist文件中涉及到的png图标、ipa安装包，是否也要上传到github上，答案是不用。经测试，官方仅验证plist所在位置是否启用SSL，其余可放到自己的服务器上，plist写好引用路径即可。

修改ipa包的bundle id  
将ipa包后缀改为.zip，解压，之后打开包文件，找到info.plist文件后，修改相应的项就可以了。把修改后的文件重新压缩成zip，把zip改为ipa，替代原来的ipa，就可以了。
如果使用itms-services安装，还需要修改对应的plist文件。
