<p align="center">
    <a href="https://openim.io">
        <img src="./assets/logo-gif/openim-logo.gif" width="60%" height="30%"/>
    </a>
</p>

<div align="center">

[![Stars](https://img.shields.io/github/stars/openimsdk/open-im-server?style=for-the-badge&logo=github&colorB=ff69b4)](https://github.com/openimsdk/open-im-server/stargazers)
[![Forks](https://img.shields.io/github/forks/openimsdk/open-im-server?style=for-the-badge&logo=github&colorB=blue)](https://github.com/openimsdk/open-im-server/network/members)
[![Codecov](https://img.shields.io/codecov/c/github/openimsdk/open-im-server?style=for-the-badge&logo=codecov&colorB=orange)](https://app.codecov.io/gh/openimsdk/open-im-server)
[![Go Report Card](https://goreportcard.com/badge/github.com/openimsdk/open-im-server?style=for-the-badge)](https://goreportcard.com/report/github.com/openimsdk/open-im-server)
[![Go Reference](https://img.shields.io/badge/Go%20Reference-blue.svg?style=for-the-badge&logo=go&logoColor=white)](https://pkg.go.dev/github.com/openimsdk/open-im-server/v3)
[![License](https://img.shields.io/badge/license-Apache--2.0-green?style=for-the-badge)](https://github.com/openimsdk/open-im-server/blob/main/LICENSE)
[![Slack](https://img.shields.io/badge/Slack-500%2B-blueviolet?style=for-the-badge&logo=slack&logoColor=white)](https://join.slack.com/t/openimsdk/shared_invite/zt-22720d66b-o_FvKxMTGXtcnnnHiMqe9Q)
[![Best Practices](https://img.shields.io/badge/Best%20Practices-purple?style=for-the-badge)](https://www.bestpractices.dev/projects/8045)
[![Good First Issues](https://img.shields.io/github/issues/openimsdk/open-im-server/good%20first%20issue?style=for-the-badge&logo=github)](https://github.com/openimsdk/open-im-server/issues?q=is%3Aissue+is%3Aopen+sort%3Aupdated-desc+label%3A%22good+first+issue%22)
[![Language](https://img.shields.io/badge/Language-Go-blue.svg?style=for-the-badge&logo=go&logoColor=white)](https://golang.org/)


<p align="center">
  <a href="./README.md">Englist</a> · 
  <a href="./README_zh_CN.md">中文</a> · 
  <a href="./docs/readme/README_uk.md">Українська</a> · 
  <a href="./docs/readme/README_cs.md">Česky</a> · 
  <a href="./docs/readme/README_hu.md">Magyar</a> · 
  <a href="./docs/readme/README_es.md">Español</a> · 
  <a href="./docs/readme/README_fa.md">فارسی</a> · 
  <a href="./docs/readme/README_fr.md">Français</a> · 
  <a href="./docs/readme/README_de.md">Deutsch</a> · 
  <a href="./docs/readme/README_pl.md">Polski</a> · 
  <a href="./docs/readme/README_id.md">Indonesian</a> · 
  <a href="./docs/readme/README_fi.md">Suomi</a> · 
  <a href="./docs/readme/README_ml.md">മലയാളം</a> · 
  <a href="./docs/readme/README_ja.md">日本語</a> · 
  <a href="./docs/readme/README_nl.md">Nederlands</a> · 
  <a href="./docs/readme/README_it.md">Italiano</a> · 
  <a href="./docs/readme/README_ru.md">Русский</a> · 
  <a href="./docs/readme/README_pt_BR.md">Português (Brasil)</a> · 
  <a href="./docs/readme/README_eo.md">Esperanto</a> · 
  <a href="./docs/readme/README_ko.md">한국어</a> · 
  <a href="./docs/readme/README_ar.md">العربي</a> · 
  <a href="./docs/readme/README_vi.md">Tiếng Việt</a> · 
  <a href="./docs/readme/README_da.md">Dansk</a> · 
  <a href="./docs/readme/README_el.md">Ελληνικά</a> · 
  <a href="./docs/readme/README_tr.md">Türkçe</a>
</p>


</div>

</p>

## Ⓜ️ About OpenIM

OpenIM is a service platform specifically designed for integrating chat, audio-video calls, notifications, and AI chatbots into applications. It provides a range of powerful APIs and Webhooks, enabling developers to easily incorporate these interactive features into their applications. OpenIM is not a standalone chat application, but rather serves as a platform to support other applications in achieving rich communication functionalities. The following diagram illustrates the interaction between AppServer, AppClient, OpenIMServer, and OpenIMSDK to explain in detail.

![App-OpenIM Relationship](./docs/images/oepnim-design.png)

## 🚀 About OpenIMSDK

**OpenIMSDK** is an IM SDK designed for **OpenIMServer**, created specifically for embedding in client applications. Its main features and modules are as follows:

+ 🌟 Main Features:

  - 📦 Local storage
  - 🔔 Listener callbacks
  - 🛡️ API wrapping
  - 🌐 Connection management

+ 📚 Main Modules:

  1. 🚀 Initialization and Login
  2. 👤 User Management
  3. 👫 Friend Management
  4. 🤖 Group Functions
  5. 💬 Conversation Handling

It is built using Golang and supports cross-platform deployment, ensuring a consistent access experience across all platforms.

👉 **[Explore GO SDK](https://github.com/openimsdk/openim-sdk-core)**

## 🌐 About OpenIMServer

+ **OpenIMServer** has the following characteristics:
  - 🌐 Microservice architecture: Supports cluster mode, including a gateway and multiple rpc services.
  - 🚀 Diverse deployment methods: Supports deployment via source code, Kubernetes, or Docker.
  - Support for massive user base: Super large groups with hundreds of thousands of users, tens of millions of users, and billions of messages.

### Enhanced Business Functionality:

+ **REST API**: OpenIMServer offers REST APIs for business systems, aimed at empowering businesses with more functionalities, such as creating groups and sending push messages through backend interfaces.
+ **Webhooks**: OpenIMServer provides callback capabilities to extend more business forms. A callback means that OpenIMServer sends a request to the business server before or after a certain event, like callbacks before or after sending a message.

👉 **[Learn more](https://docs.openim.io/guides/introduction/product)**

## :building_construction: Kiến trúc tổng thể

 Làm sâu sắc vào trái tim của chức năng Open-IM-Server với sơ đồ kiến trúc của chúng tôi.

![Overall Architecture](./docs/images/architecture-layers.png)


## :rocket: Bắt đầu nhanh

Chúng tôi hỗ trợ nhiều nền tảng. Dưới đây là các địa chỉ để trải nghiệm nhanh trên phía web：

👉 **[Demo web trực tuyến OpenIM](https://web-enterprise.rentsoft.cn/)**

🤲 Để tạo thuận lợi cho trải nghiệm người dùng, chúng tôi cung cấp các giải pháp triển khai đa dạng. Bạn có thể chọn phương thức triển khai từ danh sách dưới đây:

+ **[Hướng dẫn Triển khai Mã Nguồn](https://docs.openim.io/guides/gettingStarted/imSourceCodeDeployment)**
+ **[Hướng dẫn Triển khai Docker](https://docs.openim.io/guides/gettingStarted/dockerCompose)**
+ **[Hướng dẫn Triển khai Kubernetes](https://docs.openim.io/guides/gettingStarted/k8s-deployment)**
+ **[Hướng dẫn Triển khai cho Nhà Phát Triển Mac](https://docs.openim.io/guides/gettingstarted/mac-deployment-guide)**

## :hammer_and_wrench:  Để Bắt Đầu Phát Triển OpenIM

[![Mở trong Dev Contain](https://img.shields.io/static/v1?label=Dev%20Container&message=Open&color=blue&logo=visualstudiocode)](https://vscode.dev/github/openimsdk/open-im-server)

Mục tiêu của OpenIM là xây dựng một cộng đồng mã nguồn mở cấp cao. Chúng tôi có một bộ tiêu chuẩn, Trong [kho lưu trữ Cộng đồng](https://github.com/OpenIMSDK/community).

Nếu bạn muốn đóng góp cho kho lưu trữ Open-IM-Server này, vui lòng đọc [tài liệu hướng dẫn cho người đóng góp](https://github.com/openimsdk/open-im-server/blob/main/CONTRIBUTING.md).


Trước khi bạn bắt đầu, hãy chắc chắn rằng các thay đổi của bạn được yêu cầu. Cách tốt nhất là tạo một [cuộc thảo luận mới](https://github.com/openimsdk/open-im-server/discussions/new/choose) hoặc [Giao tiếp Slack](https://join.slack.com/t/openimsdk/shared_invite/zt-22720d66b-o_FvKxMTGXtcnnnHiMqe9Q), hoặc nếu bạn tìm thấy một vấn đề, [báo cáo nó ](https://github.com/openimsdk/open-im-server/issues/new/choose) trước.

- [Tham khảo API OpenIM](https://github.com/openimsdk/open-im-server/tree/main/docs/contrib/api.md)
- [Nhật ký Bash OpenIM](https://github.com/openimsdk/open-im-server/tree/main/docs/contrib/bash-log.md)
- [Hành động CI/CD OpenIM](https://github.com/openimsdk/open-im-server/tree/main/docs/contrib/cicd-actions.md)
- [Quy ước Mã OpenIM](https://github.com/openimsdk/open-im-server/tree/main/docs/contrib/code-conventions.md)
- [Hướng dẫn Commit OpenIM](https://github.com/openimsdk/open-im-server/tree/main/docs/contrib/commit.md)
- [Hướng dẫn Phát triển OpenIM](https://github.com/openimsdk/open-im-server/tree/main/docs/contrib/development.md)
- [Cấu trúc Thư mục OpenIM](https://github.com/openimsdk/open-im-server/tree/main/docs/contrib/directory.md)
- [Cài đặt Môi trường OpenIM](https://github.com/openimsdk/open-im-server/tree/main/docs/contrib/environment.md)
- [Tham khảo Mã Lỗi OpenIM](https://github.com/openimsdk/open-im-server/tree/main/docs/contrib/error-code.md)
- [Quy trình Git OpenIM](https://github.com/openimsdk/open-im-server/tree/main/docs/contrib/git-workflow.md)
- [Hướng dẫn Cherry Pick Git OpenIM](https://github.com/openimsdk/open-im-server/tree/main/docs/contrib/gitcherry-pick.md)
- [Quy trình GitHub OpenIM](https://github.com/openimsdk/open-im-server/tree/main/docs/contrib/github-workflow.md)
- [Tiêu chuẩn Mã Go OpenIM](https://github.com/openimsdk/open-im-server/tree/main/docs/contrib/go-code.md)
- [Hướng dẫn Hình ảnh OpenIM](https://github.com/openimsdk/open-im-server/tree/main/docs/contrib/images.md)
- [Cấu hình Ban đầu OpenIM](https://github.com/openimsdk/open-im-server/tree/main/docs/contrib/init-config.md)
- [Hướng dẫn Cài đặt Docker OpenIM](https://github.com/openimsdk/open-im-server/tree/main/docs/contrib/install-docker.md)
- [Hướng dẫn Cài đặt Hệ thống Linux OpenIM](https://github.com/openimsdk/open-im-server/tree/main/docs/contrib/install-openim-linux-system.md)
- [Hướng dẫn Phát triển Linux OpenIM](https://github.com/openimsdk/open-im-server/tree/main/docs/contrib/linux-development.md)
- [Hướng dẫn Hành động Địa phương OpenIM](https://github.com/openimsdk/open-im-server/tree/main/docs/contrib/local-actions.md)
- [Quy ước Nhật ký OpenIM](https://github.com/openimsdk/open-im-server/tree/main/docs/contrib/logging.md)
- [Triển khai Ngoại tuyến OpenIM](https://github.com/openimsdk/open-im-server/tree/main/docs/contrib/offline-deployment.md)
- [Công cụ Protoc OpenIM](https://github.com/openimsdk/open-im-server/tree/main/docs/contrib/protoc-tools.md)
- [Hướng dẫn Kiểm thử OpenIM](https://github.com/openimsdk/open-im-server/tree/main/docs/contrib/test.md)
- [Utility Go OpenIM](https://github.com/openimsdk/open-im-server/tree/main/docs/contrib/util-go.md)
- [Tiện ích Makefile OpenIM](https://github.com/openimsdk/open-im-server/tree/main/docs/contrib/util-makefile.md)
- [Tiện ích Kịch bản OpenIM](https://github.com/openimsdk/open-im-server/tree/main/docs/contrib/util-scripts.md)
- [Quản lý Phiên bản OpenIM](https://github.com/openimsdk/open-im-server/tree/main/docs/contrib/version.md)
- [Quản lý triển khai và giám sát backend](https://github.com/openimsdk/open-im-server/tree/main/docs/contrib/prometheus-grafana.md)
- [Hướng dẫn Triển khai cho Nhà Phát triển Mac OpenIM](https://github.com/openimsdk/open-im-server/tree/main/docs/contrib/mac-developer-deployment-guide.md)


## :busts_in_silhouette: Cộng đồng

+ 📚 [Cộng đồng OpenIM](https://github.com/OpenIMSDK/community)
+ 💕 [Nhóm Quan tâm OpenIM](https://github.com/Openim-sigs)
+ 🚀 [Tham gia cộng đồng Slack của chúng tôi](https://join.slack.com/t/openimsdk/shared_invite/zt-22720d66b-o_FvKxMTGXtcnnnHiMqe9Q)
+ :eyes: [Tham gia nhóm WeChat của chúng tôi (微信群)](https://openim-1253691595.cos.ap-nanjing.myqcloud.com/WechatIMG20.jpeg)

## :calendar: Cuộc họp Cộng đồng

Chúng tôi muốn bất kỳ ai cũng có thể tham gia cộng đồng và đóng góp mã nguồn, chúng tôi cung cấp quà tặng và phần thưởng, và chúng tôi chào đón bạn tham gia cùng chúng tôi mỗi tối thứ Năm.

Hội nghị của chúng tôi được tổ chức trên Slack của [OpenIM Slack](https://join.slack.com/t/openimsdk/shared_invite/zt-22720d66b-o_FvKxMTGXtcnnnHiMqe9Q) 🎯, sau đó bạn có thể tìm kiếm pipeline Open-IM-Server để tham gia

Chúng tôi ghi chú mỗi [cuộc họp hai tuần một lần](https://github.com/orgs/OpenIMSDK/discussions/categories/meeting) trong [các cuộc thảo luận GitHub](https://github.com/openimsdk/open-im-server/discussions/categories/meeting), ghi chú cuộc họp lịch sử của chúng tôi cũng như các bản ghi lại của cuộc họp có sẵn tại [Google Docs :bookmark_tabs:](https://docs.google.com/document/d/1nx8MDpuG74NASx081JcCpxPgDITNTpIIos0DS6Vr9GU/edit?usp=sharing).

## :eyes: Ai Đang Sử Dụng OpenIM

Xem trangr [các nghiên cứu trường hợp người dùng](https://github.com/OpenIMSDK/community/blob/main/ADOPTERS.md) của chúng tôi để biết danh sách các người dùng dự án. Đừng ngần ngại để lại [📝bình luận](https://github.com/openimsdk/open-im-server/issues/379) và chia sẻ trường hợp sử dụng của bạn.

## :page_facing_up: Giấy phép

OpenIM được cấp phép theo giấy phép Apache 2.0. Xem [GIẤY PHÉP](https://github.com/openimsdk/open-im-server/tree/main/LICENSE) để biết toàn bộ nội dung giấy phép.

Logo OpenIM, bao gồm các biến thể và phiên bản hoạt hình, được hiển thị trong kho lưu trữ này [OpenIM](https://github.com/openimsdk/open-im-server) dưới các thư mục [assets/logo](./assets/logo) và [assets/logo-gif](assets/logo-gif) được bảo vệ bởi luật bản quyền.

## 🔮 Cảm ơn các đóng góp của bạn!

<a href="https://github.com/openimsdk/open-im-server/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=openimsdk/open-im-server" />
</a>
