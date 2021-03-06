# 用户存留

用户存留一直是网站应用保持活跃度的一项重大课题。通过自身过硬的品质和适当的营销手段吸引到用户之后，PWA 提供了一系列方法来提高网站吸引力，增加网站与用户的互动性等等，达到提高用户留存率的目的。

## 添加到主屏幕

网站应用向来需要依附于浏览器，在一般情况下，网站首先需要打开浏览器，然后输入网址或者打开书签，才能够访问到网页内容。这一流程相比起直接占领主屏的原生应用来说简直是绕了一个大弯，这也是原生应用相对于网站应用更为方便的原因之一。因此网站应用也迫切地需要这一功能。PWA 新增了 `manifest.json` 配置文件，用于定义添加到桌面的图标和应用名称、打开应用的启动动画，并且通过修改显示类型的配置项，可以隐藏掉浏览器相关 UI（如导航栏、工具栏等等），使得从主屏幕直接打开的网站应用更像原生应用。

## 凭证管理

提高网站吸引力的方法少不了长效的账号机制建立，只有通过账号机制才能够更有效地获取并分析用户需求，从而给予更为准确的个性化服务。在这个方面，PWA 新增了凭证管理 API，提供了更为高效和安全的用户身份凭证存储和读取的功能，用以简化及优化用户登录流程，从而提高用户登录率。

## 桌面通知
<!-- FIXME: 与1.3 离线通知部分第三段重复 -->
桌面通知是一种时效性最强的与用户沟通的方式，即使在应用未打开的情况下，桌面通知依然能够在设备的通知栏显示推送的通知，能够立即引起用户的注意，对于一些突发事件、限时活动、重大升级等等时效性要求很高的场景，桌面通知总是最好的选择。这也是过去原生应用功能强于网站应用的原因之一。因此 PWA 提供了 Notification API，补全了这一功能。

## 消息推送

有了桌面通知作为消息展示的载体之后，浏览器还提供了专门的消息推送方法，使得网页即使在未打开的情况下，也能够接收到后端推送的消息，并且结合 Notification API 就能够做到离线的消息推送与通知展现了。

## 支付方法

对于用户留存来说，浏览器的支付功能就是培养用户习惯的利器，一旦用户习惯了在浏览器中使用支付 API 进行购物等消费活动，那么用户留存率自然就提高了。而且现代社会很多人都会有网上购物的需求，提供统一方便使用的支付界面是 Payment Request API 的目标之一。
