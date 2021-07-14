# Hướng dẫn viết một Lab Guide

Đây là cách cơ bản để viết một Lab Guide sử dụng Markdown.

> Đây là hướng dẫn chứ không phải là cách duy nhất để tuân thủ theo. :D Format đã được sư phụ Hưng xem xét và kiểm duyệt sau nhiều lần sửa chữa.

> Nếu thấy có điểm nào format làm đẹp hơn nhớ đóng góp cho môn phái nhá :D

#### Công cụ

1. Lab guide sử dụng [**Theme Hugo**](https://gohugo.io/) có thể được cài đặt trên nhiều nền tảng tại [đây](https://gohugo.io/getting-started/installing/) miễn sao gõ ```hugo version``` trong Terminal/CMD/PowerShell chạy được là được.
2. **Một IDE** nào đó có các plug-ins hỗ trợ các loại ngôn ngữ cho thuận tiện trong việc viết: Visual Studio Code, Atom, Notepad++,... (Người viết guide này đang xài **Visual Studio Code**)
3. **Các plug-ins theo IDE**: Để dễ dàng hơn trong việc viết markdown sẽ cần plug-ins dành cho Markdown (như **Markdown All in One**, **Markdown TOC**,...). Mỗi khi viết 1 file ngôn ngữ mới (Ví dụ: .md, Dockerfile,...) mà chưa có plugins thì thường các IDE (như VS Code) cũng gợi ý cài cái plug-ins liên quan nên không cần quá lo lắng về việc này.

#### Tài liệu

1. Tài liệu chính chủ [Hugo Documentation](https://gohugo.io/documentation/)
2. Tài liệu cho [Hugo Learn Theme](https://learn.netlify.app/en/) (Nói rõ về tổ chức, syntax cho tới shortcode (những thứ được dựng sẵn))

#### Nội dung và các bước thực hiện

1. Để bắt đầu viết Lab, hãy kiểm tra nội dung bên trong thư mục ```Number_LabName```.

> Đây sẽ là thư mục chính chứa Lab guide.

2. Sau khi cài đặt các công cụ ở trên, hãy đi vào thư mục ```Number_LabName``` và mở nó trong IDE đã được cài đặt.
3. Dùng cửa sổ lệnh và chạy lệnh ```hugo server``` để khởi chạy phần web của hướng dẫn này. Dùng trình duyệt truy cập vào http:\\\\localhost:1313 để xem kết quả.
4. Xem song song **phần nội dung markdown bằng IDE** và **phần hiển thị kết quả trên Web** để hiểu cách viết Lab guide.
