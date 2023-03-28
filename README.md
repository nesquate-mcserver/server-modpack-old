# 伺服器模組包

這是給美代子 Minecraft 伺服器使用的模組包，使用 [PackWiz](https://packwiz.infra.link/) 製作。

## 目標 Minecraft 版本

1.19.4

## 模組版本號規則

`season-main.subversion`

- `season` 為目前伺服器季度
- `main` 為主版本號，模組新增/移除時會變更此號碼
- `subversion` 為次版本號，模組更新時會變更此號碼

不同季度的模組包會放在不同的資料夾。

## 需手動更新模組列表

以下模組在 Curseforge 和 Modrinth 都找不到，需要自行到 GitHub 查閱並手動更新 URL。

| 名稱 | URL |
|:---|:---|
|carpet-autoCraftingTable|https://github.com/gnembon/carpet-autoCraftingTable|

## 需手動編譯模組列表

以下模組因為各種問題需要手動編譯

| 名稱 | URL |原因|  
|:---|:---|:---|
|fabric-permissions-api|https://github.com/lucko/fabric-permissions-api|最新 Commit 沒有釋出 Release 導致 LuckPerms 依賴炸掉|
