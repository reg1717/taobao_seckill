# taobao_seckill
淘宝、天猫半价抢购，抢电视、抢茅台，干死黄牛党
## 依赖
### 安装chrome浏览器，根据浏览器的版本找到对应的[chromedriver](http://npm.taobao.org/mirrors/chromedriver/)

## web版本使用说明
1、抢购前需要校准本地时间，然后把需要抢购的商品加入购物车  
2、如果要打包成可执行文件，可使用pyinstaller自行打包  
3、不需要打包的，直接在项目根目录下 执行 python3 main.py  
4、程序运行后，会打开淘宝登陆页，需要自己手动点击切换到扫码登陆  

## api版本使用说明
1、抢购前请

### 本人亲自测试过，下单到付款在十秒钟以内，这个速度是可以抢到很多东西了，[订单截图](https://github.com/jerry3747/taobao_seckill/blob/master/icon/order.jpg),这单的开抢时间是14:00:00

## 淘宝有针对selenium的检测，如果遇到验证码说明被反爬了，遇到这种情况应该换一个方案，凡是用到selenium的都会严重依赖网速、电脑配置。
## 如果想直接绕过淘宝的检测，可以手动打开浏览器登陆淘宝，然后再用selenium接管浏览器。只提供思路，具体实现大佬们可以自己摸索。


