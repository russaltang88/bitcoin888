### ierc-m6 挖矿指南（当前进度 0.319%）

> **进度实时查询**（需科学上网）：  
> [https://www.ierc20.com/tick/ierc-m6](https://www.ierc20.com/tick/ierc-m6)

---

#### ⚠️ 安全提示
1. **禁用网页版挖矿**（需导入私钥，已发生盗币事件）
2. 建议使用**全新钱包**操作
3. 家用电脑性能不足，需租用云服务器

---

### 🚀 云服务器租用指南
#### 推荐平台：vast.ai（支持加密货币支付）
- 注册链接：[https://cloud.vast.ai](https://cloud.vast.ai/?ref_id=88254)  
- 配置教程（直接看第三部分）：  
[https://heiyetouzi.xyz/minequainetwork/#toc-heading-15](https://heiyetouzi.xyz/minequainetwork/#toc-heading-15)

**机型建议**：
- RTX 3080 / RTX 3090（性价比之选）
- 时租约 $0.15
- 避免选择阿里云/腾讯云（无法下载挖矿程序）

---

### ⚒️ 挖矿部署流程
1. 进入服务器控制台  
![](https://ac63e02.webp.li/ierc20m6-001.png)  
![](https://ac63e02.webp.li/ierc20m6-002.png)

2. 执行安装命令：
```bash
apt update && apt install nodejs npm vim -y
npm install n -g
n stable
hash -r
node -v 
git clone https://github.com/IErcOrg/ierc-miner-js
cd ierc-miner-js
npm i -g yarn
yarn install
```

3. 配置 tokens.json
```bash
vim tokens.json
```
替换为：
```json
{
  "ierc-m4": { "workc": "0x0000", "amt": "1000" },
  "ierc-m5": { "workc": "0x00000", "amt": "1000" },
  "ierc-m6": { "workc": "0x000000", "amt": "1000" }
}
```

4. 启动挖矿程序
```bash
yarn cli wallet --set [你的ETH私钥]
yarn cli mine ierc-m6 --account [你的ETH地址]
```
![](https://gcore.jsdelivr.net/gh/btcltceth/blogassets@v0.2.26/b/img/ierc20m6-003.png)

---

### 💰 交易变现
- 实时查看资产：[https://www.ierc20.com/tick/ierc-m6](https://www.ierc20.com/tick/ierc-m6)  
- 当前市价：1 ierc-m6 ≈ 10 USDT  
- 多机部署收益倍增  
![](https://ac63e02.webp.li/ierc20m6-004.png)  
![](https://ac63e02.webp.li/ierc20m6-005.png)

---

### 延伸阅读
[2025中国十大虚拟币交易平台排名🔥](https://btc8848.com/top-10-exchanges/)  
[币圈暴富故事：从0到1100万再到负债10万](https://heiyetouzi.xyz/biquanstory001/)

---

### 热门搜索
比特币购买 | POW挖矿 | ierc挖矿 | 交易所注册 | OKX下载 | 币安教程 | 合约交易 | Web3空投 | NFT钱包 | 节点质押 | 铭文铸造 | 币圈入门教程@btc8848.com