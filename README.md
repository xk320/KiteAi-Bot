Kite AI Bot  自动交互机器人。

1、注册
[https://testnet.gokite.ai/?r=kxsQ3byj](https://testnet.gokite.ai?r=TdwTJfRZ)

2、功能
多个钱包支持（手动输入或基于文件）
代理支持（http/https/socks）
利率限制和重试机制
多个AI代理相互作用
自动问题选择

3、先决条件
Node.js (v16 or higher)  node.js（v16或更高）、npm

4、安装
Clone the repository:  克隆存储库：
git https://github.com/xk320/KiteAi-Bot.git

5、安装依赖项：
cd KiteAi-Bot
npm install

6、配置
创建一个proxies.txt文件以进行代理支持：
http://user:pass@host:port
socks5://user:pass@host:port

7、为多个钱包创建一个wallets.txt文件：
0xxxxx
0xxxxx

8、运行机器人：

npm run start

机器人将提示您：

Choose connection mode (Direct/Proxy)
选择连接模式（直接/代理）

Choose wallet input mode (Manual/File)
选择钱包输入模式（手册/文件）

Enter wallet address (if manual mode)
输入钱包地址（如果手动模式）

9配置选项
您可以在index.js中修改以下设置：
agents ：修改可用的AI代理商
intervalBetweenCycles ：相互作用周期之间的更改延迟
10、免责声明
该机器人仅用于教育目的。出于自己的风险使用，并确保符合风筝AI的服务条款。
