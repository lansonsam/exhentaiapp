# E站里站授权登录脚本

一个用于 Exhentai 的 Tampermonkey 脚本，提供自动登录、IP检测、自动刷新等功能。

[![GitHub license](https://img.shields.io/github/license/your-username/your-repo)](https://github.com/your-username/your-repo/blob/master/LICENSE)
[![Version](https://img.shields.io/badge/version-4.0-blue.svg)](https://github.com/your-username/your-repo/releases)

## 功能特点

> 简单易用，安全可靠的 Exhentai 登录助手

- 🔐 多种登录方式
  - Cookie 登录
  - 官网授权登录
  - GitHub 云端注入登录
- 🔄 自动刷新
  - 可自定义刷新间隔
  - 支持手动停止刷新
  - 显示倒计时和进度条
- 💾 数据同步
  - Cookie 数据云端加密存储
  - 多设备数据同步
  - 安全加密存储
- 🌐 IP 检测
  - 支持检测当前 IP 地址
  - 显示 IP 归属地信息
  - 显示 ASN 信息
  - 安全威胁检测
- ⚙️ 自定义设置
  - 自定义按钮颜色
  - 自定义背景图片
  - 自定义刷新间隔
  - 自定义重试次数和延迟

## 安装

> 两步即可开始使用

1. 首先安装 [Tampermonkey](https://www.tampermonkey.net/) 浏览器扩展
2. 点击 [安装脚本](https://update.greasyfork.org/scripts/502001/E%E7%AB%99%E9%87%8C%E7%AB%99%E6%8E%88%E6%9D%83%E7%99%BB%E5%BD%95.user.js)

## 使用说明

### 登录方式

#### 1️⃣ Cookie 登录
- 点击 "Cookie 登录" 按钮
- 输入 igneous、ipb_member_id 和 ipb_pass_hash
- 点击确认保存

#### 2️⃣ 官网授权登录
- 点击 "官网授权登录" 按钮
- 在弹出窗口中完成登录
- 登录成功后窗口会自动关闭

#### 3️⃣ GitHub 云端注入登录
- 点击 "GitHub 授权" 按钮
- 使用 GitHub 账号授权登录
- 从云端获取已保存的 Cookie
- 自动注入并完成登录

### 数据同步

#### 开启 GitHub 同步
- 在设置中点击 "GitHub 授权"
- 授权成功后自动创建加密 Gist
- 所有设置将自动同步到云端

#### 数据安全
- Cookie 数据经过加密后存储
- 使用 GitHub OAuth 确保安全
- 仅限本人账号访问
- 可随时撤销授权

### IP 检测

#### 配置 API Key
- 注册 [ipdata.co](https://dashboard.ipdata.co/sign-up.html) 获取 API Key
- 在设置中填入 API Key
- 点击 "测试 API Key" 验证

#### 使用 IP 检测
- 点击右下角悬浮按钮
- 或在设置中点击 "检测当前 IP"

### 自定义设置

> 点击 "设置" 按钮可以自定义以下选项

- **按钮颜色**
  - 普通状态颜色
  - 悬停状态颜色
  
- **刷新设置**
  - 刷新间隔时间
  - 最大重试次数
  - 重试延迟时间
  
- **外观设置**
  - 背景图片 URL

- **API 设置**
  - IP 检测 API Key

## 常见问题

> 使用过程中的常见问题解答

1. **为什么会 IP 检测失败？**
   - 检查是否正确配置了 API Key
   - 确认 API Key 是否有效
   - 检查网络连接是否正常

2. **如何停止自动刷新？**
   - 在刷新界面点击 "停止刷新" 按钮
   - 或刷新页面后重新设置

3. **按钮颜色设置无效？**
   - 确保输入了正确的颜色格式(如 rgba(128, 128, 128, 0.75))
   - 保存设置后刷新页面

4. **GitHub 同步失败？**
   - 检查 GitHub 授权是否过期
   - 确认网络连接是否正常
   - 尝试重新授权

## 更新日志

> 版本更新记录

### v4.0
- 新增 GitHub 云端注入功能
- 新增 Cookie 加密存储功能
- 新增按钮颜色自定义功能
- 优化界面样式和交互体验
- 移除动画效果提升性能
- 修复已知问题

### v3.5
- 优化 IP 检测功能
- 新增设置界面
- 优化用户界面

### v3.0
- 新增 IP 检测功能
- 新增基础设置功能
- 新增自动刷新功能

## 许可证

本项目采用 MIT 许可证，查看 [LICENSE](LICENSE) 文件了解更多信息。

## 作者

**牛子哥**

- GitHub: [@your-username](https://github.com/your-username)
- Email: your-email@example.com
- Blog: [your-blog.com](https://your-blog.com)

## 反馈与建议

如有问题或建议，请在 GitHub Issues 中提出。
