# 一、 项目介绍
由于开发出来的APP很容易被逆向，修改代码逻、加入广告、病毒等二次打包后发布，对开发者和用户造成一定的损失。因此我们的APP运行过程中需要进行签名校验，以及使用加解密算法对数据进行处理，从而保证访问服务端的请求是我们信任的APP。
# 包括以下内容
## I、客户端签名校验和数据加解密
1. 签名自动读取APP的证书进行签名校验
2. 与服务端的数据交互使用AES加解密
3. 结合MD5、RSA、DES生成AES的加密key，增加破解难度（开发中...）

## II、服务端数据加解密
服务端使用AES对客户端的数据进行加解密

## III、生成秘钥文件，随时替换（开发中...）
按照相应的规则生成秘钥文件

# 二、 使用方法（整理中...）


# 三、 相关博客介绍
[APP安全(一)-防二次打包（C、C++签名校验）](https://blog.csdn.net/mrRuby/article/details/104046640)

[APP安全(二)-c、c++AES实现加解密](https://blog.csdn.net/mrRuby/article/details/104064606)


# 四、 如果对你项目有帮助，可小小鼓励一下

![image](https://github.com/qiusanguo/HappyThreeSmiles/blob/master/img/alpay.png)


