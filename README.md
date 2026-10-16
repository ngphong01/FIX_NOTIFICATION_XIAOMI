# ⚡ VANPONG NOTI TURBO PRO v2.0
### Giải Pháp Khắc Phục Triệt Để Trễ Thông Báo & Cứu Tinh Nổ Đơn Tức Thì Trên Xiaomi (HyperOS / MIUI) và Android 10 – 15

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Android_10_to_15+-brightgreen?style=for-the-badge&logo=android" alt="Android Platform" />
  <img src="https://img.shields.io/badge/Compatibility-Xiaomi_HyperOS_|_MIUI_12--14-FF6900?style=for-the-badge&logo=xiaomi" alt="Xiaomi HyperOS" />
  <img src="https://img.shields.io/badge/Root_Required-NO_(Shizuku_Supported)-blue?style=for-the-badge" alt="No Root Needed" />
  <img src="https://img.shields.io/badge/Architecture-54--Layer_System_Tuning-blueviolet?style=for-the-badge" alt="Architecture" />
  <img src="https://img.shields.io/badge/Release-v2.0_Official-success?style=for-the-badge" alt="Release" />
  <a href="https://github.com/ngphong01/FIX_NOTIFICATION_XIAOMI/releases"><img src="https://img.shields.io/badge/GitHub_Releases-Download_APK-FFD700?style=for-the-badge&logo=github" alt="Download Releases" /></a>
</p>

---

## 📥 TẢI VỀ BẢN CÀI ĐẶT CHÍNH THỨC (RELEASE APK)

👉 **[Bấm vào đây để tải trực tiếp từ GitHub Releases: VanPong_NotiTurbo_v2.0_Release.apk](https://github.com/ngphong01/FIX_NOTIFICATION_XIAOMI/releases/download/v2.0/VanPong_NotiTurbo_v2.0_Release.apk)**  
*(Xem chi tiết nhật ký phát hành tại: [GitHub Releases Tag v2.0](https://github.com/ngphong01/FIX_NOTIFICATION_XIAOMI/releases/tag/v2.0))*

* **Tên file:** `VanPong_NotiTurbo_v2.0_Release.apk`
* **Dung lượng:** ~1.1 MB (Đã tối ưu hóa ProGuard/R8)
* **Phiên bản:** `v2.0.0 (Triple Auto-Grant Release)`
* **Yêu cầu hệ điều hành:** Android 10.0 (API 29) đến Android 15.0+ (API 35+)
* **Hỗ trợ thiết bị:** Xiaomi, Redmi, POCO (HyperOS 1.0, HyperOS 2.0, MIUI 12/13/14) và tất cả các dòng Samsung, Realme, OPPO, Vivo, Pixel.
* **Tác giả phát triển:** **Đào Văn Phong** (VanPong Software)
* **Bản quyền & Giấy phép:** Phát hành miễn phí hỗ trợ cộng đồng tài xế công nghệ và người dùng Android tại Việt Nam.

---

## 🎯 VẤN ĐỀ CẦN GIẢI QUYẾT LÀ GÌ?

Các dòng máy Android hiện đại, đặc biệt là **Xiaomi (HyperOS / MIUI)**, tích hợp cơ chế quản lý năng lượng và dọn dẹp RAM cực đoan (*MIUI Doze, App Hibernation, Smart Power Saver*). Khi điện thoại khóa màn hình từ 3 – 5 phút:
1. 📴 **Hệ điều hành cưỡng chế đóng băng (Freeze/Kill) các tiến trình ngầm.**
2. 🔌 **Ngắt socket kết nối Firebase Cloud Messaging (FCM Push Notification)** khiến tin nhắn Zalo, Messenger, Telegram, WhatsApp... bị trễ từ 5 đến 30 phút, chỉ khi người dùng bấm sáng màn hình mở app thì tin nhắn mới ào ạt đổ về.
3. 🚗 **Tài xế công nghệ (Grab, Be, Xanh SM, ShopeeFood, Lalamove...) bị miss cuốc, trượt đơn, nổ đơn chậm hơn tài xế khác** vì máy rơi vào trạng thái ngủ sâu (Deep Sleep).

**VanPong Noti Turbo Pro v2.0 ra đời để xóa bỏ triệt để 100% các rào cản này mà KHÔNG CẦN ROOT MÁY!**

---

## 💎 CÁC TÍNH NĂNG VÀ CÔNG NGHỆ ĐỘT PHÁ

### 1. 🛡️ Can thiệp 54 tầng nhân hệ điều hành (54-Layer System Tuning)
* **Active Standby Bucket:** Khóa trạng thái ứng dụng mục tiêu luôn ở nấc ưu tiên cao nhất (`ACTIVE`), ngăn chặn Android hạ cấp ứng dụng xuống mức `RARE` hoặc `RESTRICTED`.
* **Miễn nhiễm Doze Mode:** Tự động đăng ký ứng dụng vào danh sách trắng ngắt nguồn của hệ thống (`dumpsys deviceidle whitelist +[package]`).
* **Đặc quyền AppOps HyperOS:** Tự động mở thông tất cả các mã quyền ẩn của Xiaomi bao gồm `10008` (RUN_IN_BACKGROUND), `10022` (AUTOSTART), `10007` (WAKEUP), `OP_BOOT_COMPLETED`.
* **TCP Fast Open & Socket FCM Keep-Alive:** Tinh chỉnh thông số mạng và phát xung giữ nhịp định kỳ giúp kênh nhận thông báo Google luôn thông suốt.

### 2. ⚡ Tự động cấp quyền 3 cơ chế (Auto-Grant System)
Ứng dụng tích hợp bộ điều phối quyền thông minh 3 tầng độc quyền:
* **Cơ chế 1: Shizuku Binder IPC** dành cho máy **KHÔNG ROOT** (chiếm 90% người dùng) – thực hiện cấp quyền qua cổng Android Debug Bridge không dây cực kỳ an toàn.
* **Cơ chế 2: Root Superuser Shell** (Magisk / KernelSU / APatch) – 1 chạm cấp quyền tự động cho máy đã root.
* **Cơ chế 3: Accessibility Auto-Navigator** – Tự động thao tác cấp quyền nếu thiết bị chưa cài Shizuku.

### 3. ⏱️ Dịch vụ tuần tra ngầm 24/7 (Watchdog Guard Service)
* Chạy âm thầm bảo vệ các ứng dụng đã chọn cả ngày lẫn đêm.
* Giữ kết nối socket luôn ấm (*warm socket*), chống hệ thống ngắt tiến trình nhận đơn của tài xế.
* **Mức tiêu hao pin siêu tối ưu:** Tiêu thụ pin đo đạc thực tế `< 0.2%` pin / 24 giờ hoạt động.

### 4. 📊 Công cụ chẩn đoán chuyên sâu (Diagnostic Suite)
* **Latency Monitor (Đo độ trễ phản hồi):** Đo đạc chính xác thời gian thông báo bay tới máy, phát hiện ngay app nào đang bị nghẽn mạng.
* **System Priority Manager:** Hiển thị trực quan trạng thái cấu hình ngầm của từng ứng dụng.
* **Hoàn tác 1 chạm (Factory Restore):** Khôi phục lại toàn bộ cài đặt gốc của hệ điều hành bất kỳ lúc nào nếu muốn.

---

## 📋 BẢNG SO SÁNH HIỆU NĂNG

| Tiêu chí so sánh | Máy Xiaomi mặc định | Sau khi cài VanPong Noti Turbo |
|---|---|---|
| **Độ trễ tin nhắn Zalo / Mess khi khóa màn hình** | Trễ từ 5 – 30 phút | **Tức thì (0.1s - 0.5s)** |
| **Tốc độ nổ cuốc Grab / Be / Xanh SM** | Chậm hơn, thường xuyên trượt đơn | **Nổ ngay khi hệ thống phát đơn** |
| **Tình trạng đóng băng app khi tắt màn hình** | Bị đóng băng sau 3 phút | **Chạy mượt 24/7 không bị tắt** |
| **Yêu cầu Root máy / Mất bảo hành** | Không | **KHÔNG CẦN ROOT (Dùng Shizuku)** |
| **Mức tiêu hao pin** | Bình thường | **Không ảnh hưởng (< 0.2%/ngày)** |

---

## 📖 HƯỚNG DẪN CÀI ĐẶT & KÍCH HOẠT (CHỈ MẤT 2 PHÚT)

### 📌 Bước 1: Chuẩn bị môi trường cấp quyền

#### Trường hợp 1: Máy ĐÃ ROOT (Magisk / KernelSU / APatch)
* Bạn không cần chuẩn bị thêm gì. Khi mở ứng dụng, máy sẽ hiện thông báo xin quyền Superuser, bạn chỉ cần bấm **Cho phép (Grant)**.

#### Trường hợp 2: Máy KHÔNG ROOT (Khuyên dùng)
Bạn chỉ cần cài đặt và kích hoạt ứng dụng cầu nối **Shizuku** (Miễn phí trên Google Play, hoàn toàn không can thiệp phần cứng):
1. Cài app **Shizuku** từ Google Play Store (CH Play).
2. Vào **Cài đặt** ➔ **Cài đặt bổ sung** ➔ **Tùy chọn nhà phát triển**:
   * Bật **Gỡ lỗi USB** (USB Debugging).
   * Bật **Gỡ lỗi không dây** (Wireless Debugging).
3. Mở app **Shizuku** ➔ Bấm **Ghép nối (Pairing)** dưới mục Gỡ lỗi không dây ➔ Nhập 6 số mã ghép nối từ thông báo kéo xuống.
4. Quay lại Shizuku bấm nút **Bắt đầu (Start)** cho đến khi màn hình báo *"Shizuku đang chạy"* là xong!

---

### 📌 Bước 2: Cài đặt file APK

1. Tải file **[`VanPong_NotiTurbo_v2.0_Release.apk`](https://github.com/ngphong01/FIX_NOTIFICATION_XIAOMI/releases/download/v2.0/VanPong_NotiTurbo_v2.0_Release.apk)** từ mục Releases về máy.
2. Bấm vào file và chọn **Cài đặt**.
3. **⚠️ Xử lý lỗi "Cài đặt bị hạn chế / Restricted Settings" trên Android 13/14/15:**
   * Nếu công tắc quyền của app bị mờ không gạt được:
     1. Ra màn hình chính, **nhấn giữ 2 giây vào biểu tượng app VanPong Noti Turbo** ➔ Chọn **Thông tin ứng dụng (App Info - chữ ⓘ)**.
     2. Bấm vào dấu **3 chấm (⋮)** ở góc trên cùng bên phải màn hình.
     3. Chọn **"Cho phép cài đặt bị hạn chế" (Allow restricted settings)** ➔ Nhập mật khẩu/vân tay mở khóa màn hình.
     4. Mở lại ứng dụng và bật quyền bình thường!

---

### 📌 Bước 3: Thao tác sử dụng trong ứng dụng (4 bước)

1. **Cấp quyền hệ thống:** Mở app, bấm kết nối Shizuku (hoặc Root), cấp quyền Đọc thông báo và Quyền bỏ qua tối ưu hóa pin.
2. **Chọn ứng dụng cần bảo vệ:** Bấm vào nút màu xanh **"📱 CHỌN ỨNG DỤNG CẦN FIX"** ➔ Tích chọn các app bạn hay bị trễ (*Grab Driver, Be, Xanh SM, ShopeeFood, Zalo, Messenger, Telegram...*) ➔ Bấm **Lưu danh sách**.
3. **Kích hoạt tối ưu toàn diện:** Bấm nút lớn **"⚡ BẮT ĐẦU FIX TOÀN DIỆN"** ➔ Hệ thống sẽ tự động thực thi 54 tầng can thiệp cho đến khi đạt 100%.
4. **Bật Tuần tra bảo vệ:** Gạt công tắc **"BẬT DỊCH VỤ TUẦN TRA BẢO VỆ"** sang trạng thái **BẬT (ON)**.

---

## ❓ CÂU HỎI THƯỜNG GẶP (FAQ)

**Q: Khởi động lại điện thoại có bị mất tác dụng không?**  
*👉 A: Không! Toàn bộ cấu hình Active Bucket, Doze Whitelist và AppOps được lưu vĩnh viễn trong cơ sở dữ liệu hệ thống. Đối với máy dùng Shizuku, bạn chỉ cần mở lại Shizuku bấm "Start" là dịch vụ tuần tra tiếp tục hoạt động.*

**Q: Ứng dụng có làm nóng máy hay tốn pin không?**  
*👉 A: Hoàn toàn không! Ứng dụng không chạy vòng lặp ngốn CPU, mà trực tiếp gỡ bỏ các rào cản phân quyền của Android để hệ thống không được phép giết ứng dụng mục tiêu. Mức tiêu thụ đo đạc trung bình < 0.2%/ngày.*

**Q: Có an toàn cho tài khoản ngân hàng và dữ liệu cá nhân không?**  
*👉 A: 100% An toàn và Sạch sẽ. Ứng dụng hoạt động hoàn toàn Offline cục bộ trên máy, không kết nối máy chủ ngoài, không thu thập danh bạ, tin nhắn hay bất kỳ dữ liệu nhạy cảm nào.*

---

## 👨‍💻 TÁC GIẢ & HỖ TRỢ CỘNG ĐỒNG

* **Tác giả:** **Đào Văn Phong**
* **Dự án:** FIX NOTIFICATION XIAOMI & HYPEROS (VanPong Noti Turbo Pro)
* **Kênh hỗ trợ & Cập nhật:** [GitHub Repository](https://github.com/ngphong01/FIX_NOTIFICATION_XIAOMI)

*Chúc anh em luôn nhận tin nhắn kịp thời, anh em tài xế luôn nổ cuốc nhanh nhất và giật đơn mượt mà trên mọi nẻo đường!* 🚀✨
