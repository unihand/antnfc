# antnfc

[![Website](https://img.shields.io/badge/官网-antnfc.com-blue)](https://antnfc.com)
[![Platform](https://img.shields.io/badge/platform-iOS-lightgrey)](https://github.com/unihand/antnfc)

**antnfc** 是一款 iOS NFC 批量读写工具，专为需要高效管理大量 NFC 标签的用户设计。

---

## 🚀 核心功能

| 功能 | 说明 |
|------|------|
| **CSV 导入** | 从 Excel 或 CSV 文件批量导入数据，一键生成写卡任务 |
| **二维码导入** | 扫描官网工具生成的二维码，自动解析并准备写入 |
| **批量写入** | 支持主流 NFC 标签（NTAG21x、MIFARE 等） |
| **UID 导出** | 写卡结果导出为 CSV，包含每张标签的 UID，便于资产盘点与追溯 |

---

## 📦 快速开始

1. 从 [App Store]() 下载 antnfc
2. 准备数据（CSV 文件或官网二维码）
3. 打开 App，选择「导入」→ 选择数据源
4. 将 iPhone 靠近 NFC 标签，开始批量写入
5. 导出结果 CSV（含 UID）

---

## 🔗 相关链接

- [官方网站](https://antnfc.com)
- [在线二维码生成器](https://www.antnfc.com/transfer)

---

## 📄 CSV 格式示例

```csv
url,text
https://antnfc.com/s/001,产品A说明书
https://antnfc.com/s/002,产品B保修卡
