### 运行环境

开发语言node.js

以太坊运行环境testrpc，端口8545

###验证步骤

1.运行testrpc

2.替换transaction.js 14-16行 发送账户，秘钥，接受账户

3.cnpm install 或npm install 安装依赖

4.运行 node transaction.js

###运行结果示例
####发起签名交易
{ transactionHash:
   '0xc62c1642b336cf972d1a9ba7983e4884d214a22a470eaf4c45f9f305f6569fb4',
  transactionIndex: 0,
  blockHash:
   '0xe2a2f409379fa0d1082a3f5fd3671ee7b0eab199e80636035a31850a37a0cafd',
  blockNumber: 20,
  gasUsed: 21656,
  cumulativeGasUsed: 21656,
  contractAddress: null,
  logs: [],
  status: true }
####查询交易
{ hash:
   '0xc62c1642b336cf972d1a9ba7983e4884d214a22a470eaf4c45f9f305f6569fb4',
  nonce: 19,
  blockHash:
   '0xe2a2f409379fa0d1082a3f5fd3671ee7b0eab199e80636035a31850a37a0cafd',
  blockNumber: 20,
  transactionIndex: 0,
  from: '0xef14d3e581B97a54618363Ca2C74BDb9C1C7C4cb',
  to: '0x2112605bC9eCe4151f6A1447f22b2086504bb903',
  value: '1',
  gas: 3000000,
  gasPrice: '2000000000',
  input:
   '0x7f7465737432000000000000000000000000000000000000000000000000000000600057' }
