# Paperclip · hotmonet 订阅合集

将整个 quantumultx 文件夹上传到 hotmonet/paperclip 的 main 分支根目录。
勿将本目录的 README.md 覆盖到仓库根目录。

上传后，Quantumult X → 任务 → 任务仓库 → 添加：

```text
https://raw.githubusercontent.com/hotmonet/paperclip/refs/heads/main/quantumultx/Paperclip_BoxJs.json
```

此 JSON 同时包含上游 BoxJS 设置与 36 条 Quantumult X 任务。Cookie 规则通过 addons 关联，并包含 hostname。
任务默认关闭；添加所需任务和附带重写，安装并信任 HTTPS 解密证书，按原项目说明获取 Cookie 后，关闭该 Cookie 重写并开启任务。

签到和 Cookie JS 直接引用 MaYIHEI/paperclip 原仓库；原地址下的代码更新后，更新 QX 脚本缓存即可获取。
这里保存的是任务与抓取规则。上游新增任务、修改 cron、抓取 URL 或 hostname 时，仍需要更新本目录配置。
Fork 本身不会自动同步上游；可在 GitHub 使用 Sync fork，同步时保留本目录。

龙湖 App 与小程序的 Cookie 重写分次开启；北京华联与龙德广场二选一。
AgentRouter 和网上国网先按原项目说明配置账号；汇总无需 Cookie 附件。
上游 BoxJS 设置保留作者标注与存储键，可能包含任务中未收录的归档项目。
只做静态格式与引用检查，未在 iPhone 实机验证。
