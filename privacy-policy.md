# Triggr（安全哨兵）隐私权政策

**最后更新：2026 年 9 月 8 日**

感谢使用 Triggr（安全哨兵）。我们非常重视你的隐私。本政策说明我们在你使用应用时如何处理信息。

**核心原则：Triggr 是一款"本地优先"的应用。你的场景配置、事件记录、录音等所有数据都只保存在你的设备上。我们没有服务器，不会上传、出售或分析你的任何个人数据。**

## 一、我们处理的信息

### 1. 位置信息（定位权限）
- 应用的核心功能依赖定位：在设备本地判断你是否进入/离开预设区域（如厂区入口），以便自动触发安全提醒。
- 授予"始终允许"后，应用可在后台获取位置以持续检测围栏。
- 位置信息**仅在设备本地处理与存储**（如事件记录中的围栏距离），**不会上传到任何服务器**。
- 你可随时在系统设置中关闭定位权限；关闭后围栏功能不可用，其余功能不受影响。

### 2. 蓝牙信息
- 用于扫描入口处的蓝牙信标（iBeacon），仅读取信标的 UUID、Major、Minor 及信号强度（RSSI）。
- 不通过蓝牙识别或追踪你的个人身份。

### 3. NFC 信息
- 仅在你主动扫描 NFC 标签时读取标签的唯一标识（UID / NDEF 内容），用于绑定入口场景。
- 不读取或存储标签上的其他数据。

### 4. WiFi 信息
- 在本地读取当前连接的 WiFi 名称（SSID），用于匹配已配置的场景，或在室内时静默围栏报警。
- 不收集 WiFi 密码，不监听网络流量。

### 5. 麦克风（录音）
- 仅在你主动使用"录音提醒"功能时启用麦克风。
- 录音文件只保存在设备本地，你可随时删除。

### 6. 场景与事件数据
- 你创建的场景、装备清单、触发/确认事件等全部保存在设备本地。
- 应用不包含任何统计、埋点或行为分析功能。

### 7. 订阅与付款信息
- iOS 端订阅通过 Apple App Store 完成；Android 端通过 Google Play 完成。
- 付款信息由 Apple / Google 直接处理，我们**无法接触也绝不收集**你的支付账号、卡号等付款信息。
- 订阅状态仅保存在设备本地，用于解锁对应功能。

### 8. AI 智能助手（iOS）
- 在支持 Apple Intelligence 的设备（iOS 26 及以上）上，场景意图分析在**设备端**完成。
- 设备不支持时，应用回退到内置规则引擎，同样完全在本地运行。
- 该功能不会将你的输入上传到我们的服务器。

## 二、数据存储与安全

- 所有数据保存在设备本地存储（应用沙盒），卸载应用即被彻底删除。
- 应用没有远程服务器，不使用云存储。
- 通过"导出配置"生成的 JSON 文件由你自行保管，请勿分享给不信任的对象。
- （iOS）若你使用后续推出的 iCloud 同步功能，同步内容将通过 Apple iCloud 存储与加密，受 Apple 隐私政策约束。

## 三、第三方服务

- **iOS**：不集成任何第三方统计、广告或数据收集 SDK。地图与定位使用系统自带服务（MapKit / CoreLocation，由 Apple 提供）。
- **Android**：
  - 高德开放平台地图/定位 SDK：用于地图选点与定位展示。高德会在其隐私政策范围内处理部分设备与位置信息，详见高德官方隐私政策。
  - Google Play 结算服务：处理订阅付款，其数据处理受 Google 隐私政策约束。

## 四、儿童隐私

本应用面向工作场所安全场景，不面向 13 岁以下儿童，且不会故意收集儿童的个人信息。

## 五、政策变更

若本政策更新，我们将在本页面发布并更新"最后更新"日期。继续使用应用即表示你接受更新后的政策。

## 六、联系我们

如有任何问题、建议或隐私相关请求，请通过以下方式联系：

- 邮箱：**kitterive@qq.com**
- GitHub Issues：https://github.com/guoxiujiang1971/triggr/issues

---

*Triggr 尊重你的隐私。你的所有数据都只属于你。*

---
---

# Triggr Privacy Policy

**Last updated: September 8, 2026**

Thank you for using Triggr. This policy explains how information is handled when you use the app.

**Core principle: Triggr is a "local-first" app. All your data — scenarios, event logs, recordings — stays on your device. We have no servers and never upload, sell, or analyze your personal data.**

## 1. Information We Process

### Location
- Core functionality relies on location: the app detects locally whether you enter/leave a preset area (e.g., a factory entrance) to trigger safety reminders.
- With "Always" permission granted, the app accesses location in the background for continuous geofence monitoring.
- Location data is processed and stored **only on your device** (e.g., geofence distance in event logs) and is **never uploaded to any server**.
- You may revoke location permission at any time; geofencing stops but other features are unaffected.

### Bluetooth
- Used to detect Bluetooth beacons (iBeacon) at entrances, reading only UUID, Major, Minor, and signal strength (RSSI).
- We do not identify or track your personal identity via Bluetooth.

### NFC
- Only when you actively scan an NFC tag, its identifier (UID / NDEF content) is read to bind an entrance scenario.
- No other data on the tag is read or stored.

### Wi-Fi
- The current Wi-Fi SSID is read locally to match configured scenarios or to silence geofence alerts indoors.
- No Wi-Fi passwords are collected and no network traffic is monitored.

### Microphone
- The microphone is used only when you actively record a voice reminder.
- Recordings stay on your device and can be deleted at any time.

### Scenarios & Events
- Scenarios, equipment checklists, and trigger events are stored entirely on your device.
- The app contains no analytics, tracking, or telemetry.

### Subscriptions & Payments
- Subscriptions are completed through the Apple App Store (iOS) or Google Play (Android).
- Payment information is handled directly by Apple / Google; we **never collect** payment accounts or card details.
- Subscription state is stored locally on your device only.

### AI Assistant (iOS)
- On devices supporting Apple Intelligence (iOS 26+), intent analysis runs **on-device**.
- On unsupported devices the app falls back to a built-in rule engine, which also runs entirely locally.
- Your input is never uploaded to our servers.

## 2. Data Storage & Security

- All data resides in the app sandbox on your device and is erased when the app is uninstalled.
- The app has no remote servers and uses no cloud storage.
- JSON config files you export are yours to keep — do not share them with untrusted parties.
- (iOS) If/when iCloud sync becomes available, synced content will be stored encrypted via Apple iCloud, governed by Apple's privacy policy.

## 3. Third-Party Services

- **iOS**: No third-party analytics, advertising, or data-collection SDKs. Maps and location use system frameworks (MapKit / CoreLocation, provided by Apple).
- **Android**:
  - AMap SDK (map/location): used for map-based geofence selection and display. AMap processes certain device and location data under its own privacy policy.
  - Google Play Billing: processes subscription payments under Google's privacy policy.

## 4. Children's Privacy

This app is designed for workplace safety and is not directed to children under 13. We do not knowingly collect personal information from children.

## 5. Changes to This Policy

Updates will be posted on this page with a revised "last updated" date. Continued use of the app constitutes acceptance of the updated policy.

## 6. Contact

For questions, feedback, or privacy requests:

- Email: **kitterive@qq.com**
- GitHub Issues: https://github.com/guoxiujiang1971/triggr/issues

---

*Triggr respects your privacy. All your data belongs to you.*``
