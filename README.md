# EasySwap NFT 交易市场

围绕 NFT 买卖构建的全栈项目，包含订单簿合约、资产托管、网页市场和链上数据服务。

## 项目特点

- 支持 NFT 挂单、买家出价、订单取消与订单匹配。
- 通过订单簿和 Vault 合约配合管理 NFT 与资金，完成交易结算。
- 支持批量订单操作与撮合，配套合约测试和部署脚本。
- API 与同步服务分开运行，提供 NFT 集合、订单、成交和市场数据。
- 前端提供钱包连接、NFT 浏览和交易操作。

## 技术与目录

- `EasySwapContract/`：Solidity、Hardhat 合约与测试。
- `nft-market-fe/`：Next.js、React、TypeScript、Wagmi、Viem 前端。
- `EasySwapBackend/`：Go API 服务。
- `EasySwapSync/`：Go 链上事件索引与同步服务。
- `EasySwapBase/`：共享的 EVM、存储、日志和订单管理组件。

各模块的安装与配置见其目录内的 README。项目包含 ProjectsTask 等上游项目代码，保留原有说明与许可证。

项目包含教学代码或第三方依赖，保留原有来源说明与许可证。

RPC 与区块浏览器配置中的 `YOUR_...` 是占位符，运行或部署前请填写自己的配置。
