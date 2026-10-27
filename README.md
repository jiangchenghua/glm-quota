# GLM 额度

一个单页的 GLM Coding Plan（z.ai）额度仪表盘，给手机用。

- 数据直接来自 `api.z.ai` 的额度接口，页面本身不经过任何中转服务器；
- API Key 只存在浏览器的 localStorage 里，不会上传；
- 页面每 60 秒自动刷新，并显示下一轮额度的刷新倒计时；
- 用手机浏览器打开后「添加到主屏幕」，就是一个随时能点开的图标。

第一次打开需要粘贴一次 Coding Plan 的 API Key（z.ai 控制台 → API Keys）。
