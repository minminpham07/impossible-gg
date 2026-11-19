# impossible.gg — Find Your Game. Match Your Mood.

Dự án website học phần **Tổng quan về Công nghệ thông tin**, HSB — ĐHQG Hà Nội.
- Sinh viên: **Phạm Tuấn Minh** — **25080615**, lớp **MAS5**
- Giảng viên: **Tạ Văn Cánh**
- Demo: https://minminpham07.github.io/impossible-gg/

## Giới thiệu

Trang web tạo một hành trình chọn trò chơi theo tâm trạng và sở thích. Bản gốc được xây dựng bằng **WordPress + XAMPP + Elementor**, sử dụng Google AI Studio / Gemini API (qua plugin Impossible AI), WooCommerce, Forminator và nội dung media AI.

## Trạng thái phiên bản GitHub Pages

Đây là **bản demo tĩnh độc lập**, không phải bản xuất đầy đủ từ WordPress. Có 6 trang:
1. Trang chủ — `index.html`
2. Ultron — `journey.html` (gợi ý game bằng quy tắc trong JS, **không phải AI Gemini thực**)
3. Vision — `vision.html` (câu trả lời FAQ cục bộ)
4. Cửa hàng — `shop.html` (giỏ hàng demo localStorage, **không có thanh toán**)
5. Feedback — `feedback.html` (lưu trên trình duyệt, **không gửi về server**)
6. Giới thiệu — `about.html` (nền tảng, công nghệ, video/GIF)

Đã triển khai CSS responsive, giao diện bạc–đỏ (#941212), hiệu ứng banner bằng CSS và điều hướng giữa các trang.

## Bổ sung media gốc

Cần tải **video gốc 20 giây** lên đường dẫn `assets/ultron-hsb.mp4` trong repository. Hiện tại trang Giới thiệu có vị trí phát video nhưng file video chưa được đẩy lên repo qua kết nối này. Cần thêm GIF/hình minh họa xuất từ dự án WordPress nếu muốn giữ nguyên thiết kế.

## Giới hạn kỹ thuật

GitHub Pages chỉ phục vụ HTML/CSS/JS. Không chạy PHP, MySQL, WordPress, WooCommerce, Forminator hoặc Gemini API server-side. Để có chatbot Gemini hoạt động và nhận đơn/feedback thật, hãy dùng hosting PHP/MySQL và backend/serverless giữ **API key bí mật ở phía máy chủ**.

**Tuyệt đối không commit** `wp-config.php`, `.env`, khóa API, dữ liệu người dùng, database xuất thô.

## Xuất bản

Repository chứa `.github/workflows/pages.yml` để triển khai qua GitHub Actions. Nếu Pages chưa được bật tự động, mở **Settings → Pages → Build and deployment → Source → GitHub Actions** rồi chạy lại workflow.

## Công nghệ

WordPress · XAMPP · Elementor · HTML/CSS · JavaScript · Google AI Studio · Gemini API · Gemini Nano Banana · WooCommerce · Forminator · Simply Static · GitHub Pages.

*Dự án sinh viên — tháng 11/2026.*
