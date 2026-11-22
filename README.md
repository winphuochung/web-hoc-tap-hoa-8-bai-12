# Web/app học tập — Hóa học 8, Bài 12

**Bài 12: Phân bón hoá học**
Môn Khoa học tự nhiên 8 (phân môn Hóa học) — Chương trình GDPT 2018, sách Kết nối tri thức với cuộc sống.

Giáo viên: Lê Văn Thắng — Trường TH và THCS Phước Hưng, xã Nhơn Hội, tỉnh An Giang.

## Nội dung

Web/app học tập 6 phần: Khởi động, Khám phá, Mô phỏng, Sơ đồ tư duy, Luyện tập (10 câu trắc nghiệm tự chấm), Vận dụng.

Bài 12 không có thí nghiệm phòng lab trong SGK nên phần Mô phỏng gồm 3 nội dung tương tác đúng với bài, đều có hình minh họa SVG thay đổi theo từng bước:
1. Nhận biết bốn loại phân bón hoá học (đạm, lân, kali, NPK) — bộ phận cây được phân tác động sáng lên kèm thành phần và tác dụng.
2. Chọn phân lân theo độ pH của đất (thanh trượt pH 3,5–8,0; pH < 5,6 đất chua dùng lân nung chảy; pH 5,6–6,5 super lân hiệu quả nhất).
3. Ủ phân bón hữu cơ đúng quy trình SGK trang 55 (3 bước sắp xếp đúng thứ tự; ≈ 3 kg rác hữu cơ + ≈ 6 g chế phẩm Trichoderma – Bacillus; sau 25–30 ngày thu phân).

## Cách dùng

- Mở file `index.html` bằng trình duyệt bất kì (không cần máy chủ).
- Học sinh đăng nhập bằng Họ tên + Lớp, học 6 phần, làm 10 câu trắc nghiệm rồi nộp bài.
- **Trạng thái CHỜ /exec:** khóa hoa8-bai12 chưa có Web App URL (Google đang chặn tạo dự án Apps Script mới) nên bản này chưa gửi điểm về Google Sheets — điểm trắc nghiệm hiện chỉ lưu trên máy học sinh (điểm cao nhất). Khi có /exec, patch fetch Sheets vào `index.html` (và `.md`) theo mẫu Bài 1.

## File trong repo

- `index.html` — web/app hoàn chỉnh, tự chứa (hình ảnh nhúng base64).
- `Web_Hoc_Tap_Hoa8_Bai12.md` — bản sao toàn bộ mã nguồn kèm khóa đáp án.
- `Code.gs` — Apps Script ghi điểm về Google Sheets (dùng khi deploy Web App).
- `assets-flow/` — 3 ảnh nền gốc (JPG 1376×768) + logo giáo viên.
