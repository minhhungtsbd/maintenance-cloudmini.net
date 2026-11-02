# maintenance-cloudmini.net

Trang thông báo bảo trì chuyên nghiệp, hiệu năng cao dành cho [Cloudmini.net](https://cloudmini.net).

Trang được tối ưu riêng biệt để chạy trên **Cloudflare Pages** (hoặc bất kỳ static web hosting nào) với tốc độ phản hồi sub-second, giao diện Cyber Dark Tech hiện đại, hiệu ứng animation mượt mà và đầy đủ thông tin trấn an khách hàng về uptime của VPS & Proxy.

---

## ✨ Điểm nổi bật
- **Giao diện Cyber Tech đẳng cấp**: Phù hợp với thương hiệu hạ tầng Cloud VPS & Proxy tốc độ cao của Cloudmini.
- **Cam kết Uptime**: Hộp thông báo nhấn mạnh toàn bộ máy chủ VPS và hệ thống Proxy vẫn chạy 100% bình thường (không làm khách hàng hoang mang).
- **Bộ đếm thời gian & Tiến độ bảo trì**: Countdown timer trực quan kèm 4 bước checklist bảo trì theo thời gian thực.
- **Kênh hỗ trợ khẩn cấp 24/7**: Nút chuyển hướng nhanh sang Telegram Kỹ thuật (`@cloudminisupport`), Client Portal (`client.cloudmini.net`), Fanpage Facebook và Email hỗ trợ.
- **Trạng thái từng cụm dịch vụ (Status Node Cards)**: VPS VN, VPS US, Proxy Cluster, Web Portal.
- **Tối ưu SEO & Cache**: Đi kèm file `_headers` cấu hình sẵn `noindex, nofollow, no-cache` để đảm bảo Google không lập chỉ mục nội dung bảo trì tạm thời.

---

## 🚀 Hướng dẫn kết nối với Cloudflare Pages

1. Đăng nhập vào [Cloudflare Dashboard](https://dash.cloudflare.com/) > chọn mục **Workers & Pages**.
2. Bấm **Create application** > chọn tab **Pages** > chọn **Connect to Git**.
3. Chọn tài khoản GitHub của bạn và chọn repository: `minhhungtsbd/maintenance-cloudmini.net`.
4. Trong phần **Build settings**:
   - **Framework preset**: `None`
   - **Build command**: *(Để trống)*
   - **Build output directory**: `/` *(hoặc để trống)*
5. Bấm **Save and Deploy**. Cloudflare sẽ deploy trang bảo trì chỉ trong vòng vài giây!
6. Gắn Custom Domain:
   - Vào mục **Custom domains** trong Cloudflare Pages của project này.
   - Thêm `cloudmini.net` hoặc subdomain tùy chọn để kích hoạt trang bảo trì.
