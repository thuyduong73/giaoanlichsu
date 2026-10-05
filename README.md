# Giáo Án Studio

Ứng dụng web tĩnh tạo kế hoạch bài dạy, slide và đề kiểm tra. Mã nguồn ứng dụng được cấp phép MIT; xem `LICENSE`.

## Chạy thử

Vì trang tải `sources.json`, hãy chạy một máy chủ tĩnh thay vì mở `index.html` bằng file://. Từ thư mục này:

```powershell
py -m http.server 8080
```

Mở http://localhost:8080. Hoặc mở thư mục trong VS Code, cài Live Server, nhấp phải `index.html` rồi chọn **Open with Live Server**.

## Đưa lên GitHub Pages

Tải toàn bộ nội dung ở gốc repository. Bật Pages tại **Settings → Pages → Deploy from a branch → main → /(root)**. Website dùng địa chỉ `https://<tài-khoản>.github.io/<tên-repository>/`. Cần repository công khai nếu dùng GitHub Free.

## Học liệu và dữ liệu

`sources.json` chứa học liệu mặc định. Người dùng có thể nhập thêm DOCX, PPTX, TXT và ZIP chứa chúng. Bài soạn lưu trong localStorage của trình duyệt.

## Giấy phép nội dung

Giấy phép MIT áp dụng cho mã ứng dụng, không tự động áp dụng cho tư liệu bên thứ ba. Ảnh `assets/lich-su-viet-nam.png` được giữ theo yêu cầu thiết kế nhưng có watermark KidsUP. Chỉ công bố ảnh này nếu bạn có quyền phân phối; nếu không, xóa ảnh và thay bằng ảnh bạn được phép dùng. Thư viện đi kèm giữ giấy phép riêng; xem `THIRD_PARTY_NOTICES.md` và `licenses/`.

## Giới hạn

Ứng dụng chạy phía trình duyệt; chưa tích hợp API AI, tài khoản, đồng bộ máy chủ hay cơ sở dữ liệu. Giáo viên cần rà soát nội dung, đáp án, ma trận và quy định kiểm tra tại địa phương trước khi dùng.
