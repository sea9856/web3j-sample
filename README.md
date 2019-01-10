# web3j-sample
web3 for java 样例程序 (基于web3j 3.4.0)   
环境 idea maven  
运行前提 需要有一个开启RPC或者IPC服务的以太坊节点

- [QuickStart](https://github.com/ethjava/web3j-sample/blob/master/src/main/java/com/ethjava/QuickStart.java) 快速开始

- [AccountManager](https://github.com/ethjava/web3j-sample/blob/master/src/main/java/com/ethjava/AccountManager.java) 账号相关接口
- [TransactionClient](https://github.com/ethjava/web3j-sample/blob/master/src/main/java/com/ethjava/TransactionClient.java) eth转账相关接口
- [TokenClient](https://github.com/ethjava/web3j-sample/blob/master/src/main/java/com/ethjava/TokenClient.java) token代币相关查询及转账
- [ColdWallet](https://github.com/ethjava/web3j-sample/blob/master/src/main/java/com/ethjava/ColdWallet.java) 冷钱包创建、交易
- [TokenBalanceTask](https://github.com/ethjava/web3j-sample/blob/master/src/main/java/com/ethjava/TokenBalanceTask.java) 批量token代币余额查询
- [EthInfo](https://github.com/ethjava/web3j-sample/blob/master/src/main/java/com/ethjava/EthInfo.java) 连接节点的相关信息接口
- [Security](https://github.com/ethjava/web3j-sample/blob/master/src/main/java/com/ethjava/Security.java) 公钥私钥相关接口
- [EthMnemonic](https://github.com/ethjava/web3j-sample/blob/master/src/main/java/com/ethjava/EthMnemonic.java) 生成、导入助记词(需要比特币的jar包 可以查看pom.xml)
- [Filter](https://github.com/ethjava/web3j-sample/blob/master/src/main/java/com/ethjava/Filter.java) 新块、新交易相关监听
- [ContractEvent](https://github.com/ethjava/web3j-sample/blob/master/src/main/java/com/ethjava/ContractEvent.java) 执行合约相关log监听
- [DecodeMessage](https://github.com/ethjava/web3j-sample/blob/master/src/main/java/com/ethjava/DecodeMessage.java) 加密后的交易数据解析
- [IBAN](https://github.com/ethjava/web3j-sample/blob/master/src/main/java/com/ethjava/IBAN.java) 根据官方规则生成iban及付款二维码
- [Calculate](https://github.com/ethjava/web3j-sample/blob/master/src/main/java/com/ethjava/Calculate.java) 在发布合约前计算合约地址，根据签名后的交易信息计算TxHash

基本功能demo已完成

打赏 eth地址:0x248F272180db4D079443753336c5C847A080275c



![mahua](mahua-logo.jpg)
##MaHua是什么?
一个在线编辑markdown文档的编辑器

向Mac下优秀的markdown编辑器mou致敬

##MaHua有哪些功能？

* 方便的`导入导出`功能
    *  直接把一个markdown的文本文件拖放到当前这个页面就可以了
    *  导出为一个html格式的文件，样式一点也不会丢失
* 编辑和预览`同步滚动`，所见即所得（右上角设置）
* `VIM快捷键`支持，方便vim党们快速的操作 （右上角设置）
* 强大的`自定义CSS`功能，方便定制自己的展示
* 有数量也有质量的`主题`,编辑器和预览区域
* 完美兼容`Github`的markdown语法
* 预览区域`代码高亮`
* 所有选项自动记忆

##有问题反馈
在使用中有任何问题，欢迎反馈给我，可以用以下联系方式跟我交流

* 邮件(dev.hubo#gmail.com, 把#换成@)
* QQ: 287759234
* weibo: [@草依山](http://weibo.com/ihubo)
* twitter: [@ihubo](http://twitter.com/ihubo)

##捐助开发者
在兴趣的驱动下,写一个`免费`的东西，有欣喜，也还有汗水，希望你喜欢我的作品，同时也能支持一下。
当然，有钱捧个钱场（右上角的爱心标志，支持支付宝和PayPal捐助），没钱捧个人场，谢谢各位。

##感激
感谢以下的项目,排名不分先后

* [mou](http://mouapp.com/) 
* [ace](http://ace.ajax.org/)
* [jquery](http://jquery.com)

##关于作者

```javascript
  var ihubo = {
    nickName  : "草依山",
    site : "http://jser.me"
  }
```
