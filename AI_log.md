# AI LOG – BUỔI 7, TIẾT 3

> Điền vào `[ ... ]`, tích `[x]` vào lựa chọn phù hợp. Ghi đúng việc đã làm; chưa kiểm tra thì ghi “Chưa kiểm tra”. Không cần chép toàn bộ cuộc trò chuyện AI.

## Thông tin sinh viên

- Họ và tên: Đỗ Trung Kiên
- Mã sinh viên – Lớp: 2071020107 - Lớp CNTT 20-02
- Ngày thực hiện: 30/10/2026
- Link repository: https://github.com/poscherclassic/K20_portfolio_CNTT_20-02.git
- URL website: https://poscherclassic.github.io/K20_portfolio_CNTT_20-02/
- Tình huống: Website của tôi còn sai link css

## 1. Nhận định của tôi trước khi hỏi AI

- Trang/thao tác gặp lỗi: nó không hiển thị css
- Mong muốn và hiện tượng thực tế: muốn có css hiển thị trên trang web
- Dữ kiện đã kiểm tra (cấu trúc tệp, Request URL, Status…): Trong `index.html`, thẻ nạp CSS đang dùng đường dẫn tuyệt đối `D:\CNTT20-04\portfolio\css\style.css`. Trong repository có thư mục `css` và tệp `css/style.css`. Request URL và Status trên Network chưa được cung cấp nên chưa xác nhận được trình duyệt nhận phản hồi nào.
- Tôi nghi nguyên nhân là: Đường dẫn tuyệt đối trên máy Windows không trỏ tới tệp CSS khi website chạy trên GitHub Pages.
- Vì sao tôi nhận định như vậy: Đường dẫn trong HTML gắn với một vị trí cụ thể trên máy, trong khi tệp CSS nằm trong thư mục `css`.
## 2. Tôi hỏi AI và nhận được gợi ý

- Nguồn: [x] Công cụ AI: Copilot  [ ] Phản hồi mẫu của giảng viên
- Câu hỏi/prompt tôi đã gửi (hoặc tình huống của phản hồi mẫu):

  Tôi có URL GitHub Pages và repository; trang không hiển thị CSS. Hãy nêu giả thuyết, dữ kiện cần kiểm tra và bản sửa tối thiểu. Chỉ tư vấn, không sửa tệp và không kết luận đã sửa thành công.

- Gợi ý chính của AI:

  Kiểm tra đường dẫn stylesheet trong HTML và vị trí tệp CSS trong repository. và đề xuất câu lệnh sửa

## 3. Quyết định của tôi

- [ ] Chấp nhận gợi ý

- Tôi quyết định làm gì: tôi đã sửa theo gợi ý
- Lý do, dựa trên dữ kiện nào: dựa trên kiến thức tôi có

## 4. Thực hiện và kiểm chứng

- Tệp/vị trí đã sửa (không sửa thì ghi rõ): Chưa sửa tệp trong quá trình trao đổi với AI.
- Nội dung thay đổi hoặc cách xử lý khác: AI đề xuất đổi `href` của stylesheet thành `css/style.css` trong `index.html` và `ket-qua.html`; chưa có thông tin xác nhận người dùng đã thực hiện.
- Commit của bản sửa, nếu có: Chưa có thông tin về commit cho bản sửa này.
- Bản sửa đã deploy: [ ] Có  [ ] Chưa  [x] Không phát sinh bản sửa trong quá trình trao đổi với AI

| Nội dung kiểm tra | Trước xử lý | Sau xử lý/thử lại |
| --- | --- | --- |
| Request URL và Status của tài nguyên liên quan | Chưa được cung cấp/chưa kiểm tra trong trao đổi | Chưa thử lại; chưa có dữ liệu |
| Giao diện/chức năng trên URL website | Theo mô tả của tôi: CSS không hiển thị | Chưa thử lại; chưa có kết quả xác nhận |

- Cách thử lại và kết quả thực tế: Chưa có thông tin về lần thử lại. Để kiểm chứng, mở DevTools → Network, lọc CSS, tải lại website và ghi Request URL/Status; sau đó quan sát giao diện. Không ghi kết quả trước khi thực sự thử.
- Căn cứ để đối chiếu (URL tệp, commit, đường dẫn ảnh chụp hoặc dữ kiện quan sát): Repository `https://github.com/poscherclassic/K20_portfolio_CNTT_20-02.git`; URL website `https://poscherclassic.github.io/K20_portfolio_CNTT_20-02/`; đường dẫn trong `index.html` là `D:\CNTT20-04\portfolio\css\style.css`; repository có `css/style.css`. Chưa có ảnh chụp Network, commit sửa hoặc dữ kiện sau khi thử lại.

## 5. Kết luận

- [ ] Đã xử lý được  [ ] Xử lý được một phần  [x] Chưa xử lý được/chưa kiểm chứng theo thông tin hiện có
- Điều tôi rút ra hoặc việc cần làm tiếp: Dùng đường dẫn tương đối tới tệp CSS thay vì đường dẫn máy cục bộ nếu Network xác nhận request sai; kiểm tra lại cả hai trang HTML, thử website sau khi áp dụng và ghi Request URL/Status cùng kết quả thực tế. Chưa thể kết luận đã xử lý thành công.

---

*Tệp là minh chứng MC2 để nhận định mức đạt của tiết học; không tính điểm MC2 riêng. Nếu có tình huống khác, sao chép mục 1–5 để ghi thêm.*
