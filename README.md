# E-commerce UI Improvement

## 1. Giới thiệu
Dự án này thực hiện cải tiến thiết kế giao diện cho thẻ sản phẩm (Product Card) trên nền tảng web di động, giúp thông tin hiển thị trực quan và tối ưu trải nghiệm thao tác của người dùng hơn.

## 2. Website tham khảo
- **Tên website:** Coolmate
- **URL:** https://www.coolmate.me/
- **Khu vực đã khảo sát:** Thẻ sản phẩm trên Trang chủ và Danh mục.

## 3. Chức năng
- Hiển thị danh sách 4 sản phẩm mẫu theo dạng lưới (Grid).
- Hiển thị đầy đủ hình ảnh, tên sản phẩm (giới hạn 2 dòng), giá bán và nút thao tác.
- Bố cục tự động tương thích (Responsive) hỗ trợ nhiều kích thước màn hình: hiển thị 4 cột trên máy tính và 2 cột trên điện thoại di động.

## 4. Công nghệ
- HTML5
- CSS3

## 5. Cách chạy
- Giải nén thư mục (nếu có).
- Mở file `index.html` bằng bất kỳ trình duyệt web nào (Chrome, Edge, Safari...).

## 6. Cải tiến đã thực hiện
- **Vấn đề ban đầu:** Trên phiên bản di động của website tham khảo, thẻ sản phẩm hiển thị quá nhiều thông tin phụ (chất liệu, lượt bán, đánh giá) khiến giao diện bị rối mắt. Nút mua hàng khá nhỏ.
- **Thay đổi đã thực hiện:** Tối giản thông tin trên thẻ (chỉ giữ lại ảnh, tên, giá). Thiết kế lại nút "Mua ngay" to bản, tràn viền và sử dụng màu đen nhận diện thương hiệu để tăng diện tích thao tác (touch target) cho người dùng điện thoại.

## 7. Hỗ trợ từ AI
- Sử dụng AI để sinh ra cấu trúc HTML cơ bản và bộ khung CSS chia lưới sản phẩm ban đầu.
- Bản thân tôi đã tự kiểm tra giao diện bằng Chrome DevTools, tự điều chỉnh CSS ở khu vực nút bấm và tinh chỉnh lại khoảng cách (margin/padding) giữa các thành phần.
