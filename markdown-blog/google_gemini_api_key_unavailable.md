# Google Gemini AI Studio API Key 一直显示 “不可用”（Unavailable”）怎么解决？

**背景说明**：4 月份，新注册了一个 Google 账号，准备使用 Google AI Studio 的 API Key。

**问题及现象**：结果发现，API Key 创建成功后，一直显示 “Unavailable（不可用）”。

<img width="2550" height="1188" alt="image" src="https://github.com/user-attachments/assets/34f889d2-4920-4d53-99e1-895069469a0d" />

<br><br>
一开始以为只是新账号限制，过几天会自动恢复，但等了很久依然无法使用。

 

为了排查这个问题，期间尝试过很多方法，包括：

- 更换手机号重新注册 Google 账号

- 使用浏览器无痕模式注册

- 在 Google Cloud Console 创建项目并开启 Gemini API

- 更换不同 VPN 节点（美国、日本、新加坡等）

- 找海外朋友本地环境测试登录

- 查询 Reddit 和开发者论坛上的相关讨论

- 检查 Google 账号年龄验证

- 检查 AI Studio 的地区可用性限制

- 研究绑定结算账号、Visa 卡等方案

但这些方法，基本都没有明显效果。

后面陆续测试了多个账号、网络环境以及设备组合后，
发现这个问题并不只是“是否绑定 Visa 卡”这么简单。

<br><br>


目前看下来：

- Google 账号本身的风控逻辑，
- 和 Google AI Studio 的风控逻辑，
很可能并不是同一套系统。

也就是说：

即使 Google 账号本身可以正常使用，
AI Studio 依然可能会把账号判定为低可信环境，
从而导致 API Key 无法正常调用。

<br><br>

后来经过多轮测试，
最终成功让 API Key 可用，如下图：
<img width="1600" height="720" alt="image" src="https://github.com/user-attachments/assets/ede8f7e6-9546-4730-9ec6-00c081b6eb60" />

我也帮助了2个朋友成功解决了这个问题，

不过，目前还无法完全100%的确定这个方法百分百可靠。

 
如果你也有这个问题，可以一起交流下。

微信：13240133388 <br>
备注：api

或许我能帮助你。
