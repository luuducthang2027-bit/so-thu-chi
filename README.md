# Sổ Thu Chi · Money Book · Kaye Lajan

Web app ghi thu chi hàng tháng, nhiều tài khoản, giao diện Việt / English / Kreyòl ayisyen.

- Giao diện: `index.html` (chạy trên GitHub Pages)
- Dữ liệu: Google Sheet, qua Google Apps Script (backend không nằm trong repo này)
- Admin xem được dữ liệu mọi tài khoản; tài khoản thường chỉ thấy dữ liệu của mình
- Báo cáo theo ngày, tuần, tháng, quý, năm hoặc khoảng tùy chọn; lịch thu chi từng ngày (xanh = thu, đỏ = chi)
- Biểu đồ thu chi, chi theo loại, 6 tháng gần nhất; xuất CSV

Cấu hình: mở `index.html`, điền URL Web App Apps Script vào `const API_URL = ''`. Để trống thì app chạy chế độ demo.
