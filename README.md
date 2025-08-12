
# Bộ Sưu Tập Project Frontend Cơ Bản

Đây là các project giao diện người dùng (frontend) do mình tự thiết kế và thực hiện khi mới bắt đầu học lập trình web (khởi tạo từ năm 2021). Tất cả đều sử dụng HTML, CSS và JavaScript thuần, tập trung vào các hiệu ứng giao diện đẹp mắt, đơn giản, dễ hiểu, phù hợp cho người mới học hoặc muốn thực hành nâng cao kỹ năng thiết kế web. Repo hiện được cập nhật lại năm 2025 để chuẩn hóa tài liệu và bổ sung định hướng học tập.


## Danh sách các project

- **Amazing Working Digital Clock using Html CSS SVG & Javascript**: Đồng hồ số động với hiệu ứng SVG.
- **Animated Circular Navigation Menu using Html CSS & Vanilla Javascript**: Menu điều hướng hình tròn với hiệu ứng động.
- **Animated Magic Menu Indicator**: Thanh menu với hiệu ứng chỉ báo động.
- **CSS Input Field Text and Gradient Border Animation Effects**: Hiệu ứng trường nhập liệu và viền gradient.
- **Dashboard Sidebar Menu using Html CSS & Vanilla Javascript**: Sidebar menu cho dashboard hiện đại.
- **Dropdown Menu using Html CSS**: Menu thả xuống với hiệu ứng đẹp mắt.
- **Dropdown Menu using Html CSS & Vanilla Javascript**: Menu thả xuống có tương tác JavaScript.
- **Focus CSS Text Hover Transition Effects**: Hiệu ứng chuyển động khi hover vào text.
- **Magic Navigation Menu Indicator using Html CSS & Javascript**: Menu điều hướng với hiệu ứng magic indicator.
- **Neumorphism Calculator using Html CSS & Javascript**: Máy tính với hiệu ứng neumorphism.
- **SS Magic Line Icon Hover Effects**: Hiệu ứng hover icon với magic line.


## Hướng dẫn sử dụng

1. Chọn project bạn muốn xem.
2. Mở file `index.html` trong trình duyệt để trải nghiệm giao diện và hiệu ứng.
3. Có thể chỉnh sửa file `style.css` hoặc `script.js` để tùy biến thêm.


## Định hướng cho người mới
- Hãy thử tự code lại các project này mà không copy, để hiểu rõ từng dòng code.
- Sáng tạo thêm hiệu ứng hoặc chức năng mới dựa trên các ví dụ này.
- Đừng ngại thử nghiệm và mắc lỗi, vì đây là cách học tốt nhất!

## Đóng góp
Bạn có thể fork repository này và gửi pull request để đóng góp thêm các project giao diện mới hoặc cải tiến các project hiện tại.

---

**Chúc các bạn mới học lập trình sẽ tìm thấy cảm hứng và động lực từ những project nhỏ này!**

## Timeline
- 2021: Bắt đầu tạo các project đầu tiên khi mới làm quen HTML/CSS/JS.
- 2022: Bổ sung thêm hiệu ứng animation và luyện tập DOM nhiều hơn.
- 2023: Sắp xếp lại cấu trúc, tinh chỉnh CSS cho gọn hơn.
- 2024: Ít cập nhật, chủ yếu giữ nguyên để tham chiếu.
- 2025: Tổng hợp & viết lại README, thêm checklist kỹ năng và gợi ý mở rộng.

---

## Cấu trúc thư mục (rút gọn)
```
Amazing Working Digital Clock .../
Animated Circular Navigation Menu .../
Animated Magic Menu Indicator/
CSS Input Field Text and Gradient Border Animation Effects/
Dashboard Sidebar Menu .../
Dropdown Menu using Html CSS/
Dropdown Menu using Html CSS & Vanilla Javascript/
Focus  CSS Text Hover Transition Effects/
Magic Navigation Menu Indicator using Html CSS & Javascript/
Neumorphism Calculator .../
SS Magic Line Icon Hover Effects/
```
Mỗi thư mục thường gồm: `index.html`, `style.css`, (tùy project) `script.js`, và đôi khi thư mục `img/` hoặc `image/`.

## Mục tiêu học tập
- Thành thạo cấu trúc HTML cơ bản & semantic đơn giản.
- Ôn luyện CSS (layout, flex, transition, animation, pseudo-elements).
- Làm quen JavaScript DOM: chọn phần tử, lắng nghe sự kiện, thao tác class, thời gian (setInterval), tính toán đơn giản.
- Tối ưu tư duy tách riêng phần giao diện và hành vi.

## Checklist kỹ năng (đánh dấu sau khi bạn đã hiểu)
- [ ] Sử dụng Flexbox / Positioning để căn chỉnh.
- [ ] Tạo và tinh chỉnh animation với `@keyframes`.
- [ ] Thao tác lớp CSS bằng `classList.add/remove/toggle`.
- [ ] Lấy thời gian thực với `Date()` (project đồng hồ).
- [ ] Hiệu ứng hover tinh tế (opacity, transform, transition timing).
- [ ] Vẽ / sử dụng SVG cơ bản (nếu có trong đồng hồ).
- [ ] Tư duy responsive đơn giản bằng media queries.

## Gợi ý mở rộng
| Chủ đề | Ý tưởng nâng cấp |
|--------|------------------|
| Đồng hồ | Thêm chế độ dark / light, định dạng 12h/24h, đồng hồ analog.| 
| Menu tròn | Thêm animation mở theo quỹ đạo, hỗ trợ bàn phím (accessibility).|
| Magic indicator | Thêm lưu trạng thái tab sau khi reload (localStorage).|
| Input effects | Thêm validate realtime & thông báo lỗi nhỏ gọn.|
| Neumorphism calculator | Thêm bàn phím ảo trên mobile & lịch sử phép tính.|
| Dropdown | Đóng khi click ra ngoài / nhấn Esc.|

## Chạy nhanh các project
Bạn có thể mở trực tiếp file `index.html` (double-click). Tuy nhiên để tránh lỗi đường dẫn tương đối trong một số trường hợp, có thể dùng một HTTP server đơn giản:

### PowerShell (Python)
Nếu đã cài Python:
```
python -m http.server 5500
```
Sau đó truy cập: http://localhost:5500 và điều hướng đến thư mục project.

### Live Server (VS Code)
1. Cài extension Live Server.
2. Mở file `index.html` bất kỳ.
3. Chuột phải chọn “Open with Live Server”.

## Lưu ý tối ưu nhỏ
- Gom màu sắc / biến lặp lại thành CSS custom properties (`:root { --primary: ... }`).
- Giảm số animation không cần thiết để tiết kiệm tài nguyên.
- Đặt script cuối `body` hoặc dùng `defer` để tăng tốc tải.
- Thêm `lang="vi"` trong thẻ `<html>` để hỗ trợ SEO / accessibility.

## License
Bạn có thể sử dụng, chỉnh sửa, chia sẻ lại cho mục đích học tập cá nhân. Nếu dùng công khai, vui lòng ghi nguồn hoặc để lại link về repository này.

## Liên hệ / Kết nối
- GitHub: (thêm link của bạn)
- Email: (thêm email nếu muốn)
- Ghi chú cá nhân: “Code chậm mà chắc – hiểu bản chất quan trọng hơn hoàn thành nhanh.”

---

Nếu bạn muốn mình viết thêm phần tiếng Anh, chuyển sang cấu trúc nâng cao hơn (framework), hoặc gộp build tool, cứ nói nhé.
