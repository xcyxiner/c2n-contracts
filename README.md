# c2n-contracts

## node版本
node 18.19

## 1空项目初始化
可以全局安装hardhat

```
npx hardhat init
```
## 2安装相关依赖和插件

删除 自带的hardhat-toolbox，并安装相关的依赖

```
安装智能合约开发所需的插件： 该项目中使用了 Hardhat 的一些插件，以支持以太坊智能合约的开发和测试。
npm install --save-dev hardhat
npm install --save @nomiclabs/hardhat-waffle @nomiclabs/hardhat-web3
npm install --save-dev @nomiclabs/hardhat-ethers
npm install --save-dev @openzeppelin/hardhat-upgrades@1

安装以太坊智能合约库： 项目中使用了 OpenZeppelin 的智能合约库，用于编写和部署智能合约。
npm install --save-dev @openzeppelin/contracts @openzeppelin/contracts-upgradeable

安装其他测试相关的库： 项目中还引用了一些测试相关的库，如 chai、ethereum-waffle 等。
npm install --save-dev chai bn-chai chai-as-promised chai-bignumber chai-bn ethereum-waffle

安装以太坊 JavaScript 库： ethers 是一个以太坊 JavaScript 库，用于与以太坊网络进行交互。
npm install --save-dev ethers@5

其他依赖： 此外，项目中还引用了 dotenv 用于环境变量管理，以及 yesno 用于简单的交互式命令行提示。
npm install --save dotenv yesno
```

## remix 编辑