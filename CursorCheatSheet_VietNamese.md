# Cheat Sheet Cursor AI

## I.Câu hỏi
- [1. Cursor AI là gì?](#1-cursor-ai-là-gì)
- [2. Premium Requests là gì?](#2-premium-requests-là-gì)

## II.Tips
- [1. Add nhiều đoạn code, script vào để hỏi cùng một lượt?](#1-add-nhiều-đoạn-code-script-vào-để-hỏi-cùng-một-lượt)
- [2. Có thể chỉnh sửa câu hỏi lại nếu bạn không vừa ý câu trả lời của AI](#2-có-thể-chỉnh-sửa-câu-hỏi-lại-nếu-bạn-không-vừa-ý-câu-trả-lời-của-ai)
- [3. Tối ưu hóa tài nguyên token](#3-tối-ưu-hóa-tài-nguyên-token)

<br>

## Câu hỏi
### 1. Cursor AI là gì?<br>
Cursor AI là một trình soạn thảo mã nguồn tích hợp trí tuệ nhân tạo (AI), được xây dựng dựa trên VS Code, giúp lập trình viên viết code nhanh hơn, sửa lỗi thông minh hơn và tối ưu hóa code hiệu quả hơn.
Tính năng chính của Cursor AI.<br>
1️⃣ Tự động hoàn thành mã (Cursor Tab)<br>
&emsp;✔️ Gợi ý cả đoạn code dài, không chỉ một vài dòng như Copilot.<br>
&emsp;✔️ Có thể chỉnh sửa mã xung quanh, không chỉ chèn thêm.<br>
&emsp;✔️ Hỗ trợ viết lại đoạn code theo hướng tối ưu hơn.<br>

2️⃣ Chat AI trực tiếp trong trình soạn thảo<br>
&emsp;✔️ Đặt câu hỏi về code ngay trong editor.<br>
&emsp;✔️ Yêu cầu AI giải thích thuật toán, sửa lỗi hoặc viết code mới.<br>
&emsp;✔️ Hỗ trợ chat có ngữ cảnh toàn bộ project, giúp AI hiểu rõ hơn.<br>

3️⃣ Shadow Workspace – AI chạy code trong nền<br>
&emsp;✔️ AI có thể thử nghiệm code mà không làm ảnh hưởng đến mã nguồn chính.<br>
&emsp;✔️ Hỗ trợ kiểm tra lỗi, gợi ý chỉnh sửa và tối ưu hóa code một cách tự động.<br>

4️⃣ Tìm kiếm thông minh trong codebase<br>
&emsp;✔️ Tìm kiếm theo ngữ nghĩa thay vì chỉ dựa trên từ khóa.<br>
&emsp;✔️ Hỗ trợ nhận diện hàm, biến và các tài liệu liên quan nhanh chóng.<br>

5️⃣ Tích hợp nhiều mô hình AI mạnh mẽ<br>
&emsp;✔️ Hỗ trợ GPT-4, GPT-4o, Claude 3.5 Sonnet – những mô hình AI tốt nhất hiện nay.<br>
&emsp;✔️ Cho phép chọn mô hình AI phù hợp với nhu cầu sử dụng.<br>
<br>

### 2. Premium Requests là gì?  
Premium Requests là các yêu cầu sử dụng mô hình AI cao cấp trong Cursor, thường liên quan đến:<br>
&emsp;✔️ GPT-4, GPT-4o, Claude 3.5 Sonnet (các mô hình mạnh nhất).<br>
&emsp;✔️ Các tác vụ phức tạp như phân tích code chuyên sâu, viết lại đoạn code dài, giải thích thuật toán khó.<br>
&emsp;✔️ Tăng tốc độ xử lý so với các mô hình miễn phí (cursor-small).<br>
- Yêu cầu nhanh (Fast Premium Requests)<br>
&emsp;✔️ Được ưu tiên xử lý ngay lập tức, đảm bảo tốc độ phản hồi cao.<br>
&emsp;✔️ Số lượng giới hạn theo gói đăng ký (ví dụ: 500 yêu cầu/tháng cho gói Pro).<br>
&emsp;✔️ Khi hết hạn, người dùng chuyển sang yêu cầu chậm hoặc kích hoạt tính năng trả phí theo lượt dùng.<br>
- Yêu cầu chậm (Slow Premium Requests)<br>
&emsp;✔️ Xử lý trong hàng đợi khi hệ thống quá tải hoặc người dùng đã dùng hết Fast Requests.<br>
&emsp;✔️ Không giới hạn số lượng (trừ gói Hobby), nhưng thời gian chờ tăng dần theo số lượt đã sử dụng.<br>
Các mô hình Premium được tính vào Premium Requests<br>
&emsp;▶ GPT-4/GPT-4o: Mô hình xử lý đa nhiệm, phù hợp với code generation và phân tích logic phức tạp.<br>
&emsp;▶ Claude 3.5 Sonnet: Tối ưu cho tác vụ yêu cầu độ chính xác cao và xử lý ngữ cảnh dài.<br>
&emsp;▶ Claude 3 Opus: Dành cho tác vụ chuyên sâu (giới hạn 10 lượt/ngày với gói Pro).<br>
&emsp;▶ Claude 3.5 Haiku: Mỗi lượt gọi tính bằng 1/3 Fast Request.<br>
&emsp;▶ O1-mini: Giới hạn 10 lượt/ngày (gói Pro).<br>
Cách tính Premium Requests<br>
&emsp;▶ Gói Hobby: 50 Slow Premium Requests miễn phí/tháng.<br>
&emsp;▶ Gói Pro: 500 Fast Premium Requests + Unlimited Slow Requests.<br>
&emsp;▶ Gói Business: Tương tự Pro, thêm tính năng quản lý tập trung và chế độ riêng tư.<br>
Mô hình đặc biệt:<br>
&emsp;▶ Claude 3.5 Haiku: 1 lượt gọi = 1/3 Fast Request.<br>
&emsp;▶ Claude 3 Opus: Sử dụng 10 lượt/ngày (gói Pro).<br><br>
🔗 Chi tiết mức giá cho các model https://docs.cursor.com/settings/models
<br><br><br>

## Tips<br>
### 1. Add nhiều đoạn code, script vào để hỏi cùng một lượt? 
&emsp;▶ Bôi đoạn code và thao tác add hoặc nhấn phím tắt Ctrl+Shift+L để đính kèm thêm vào câu hỏi để AI hiểu rõ ngữ cảnh hơn<br>
[Back to II. Tips](#iitips)

### 2. Có thể chỉnh sửa câu hỏi lại nếu bạn không vừa ý câu trả lời của AI
&emsp;▶ Ở tab chat với cursor. Bạn có thể edit lại câu hỏi hoặc thêm ngữ cảnh (code, function, script) vào để giúp cho câu trả lời của AI chính xác hơn<br>
[Back to II. Tips](#iitips)

### 3. Tối ưu hóa tài nguyên token
🔴 Một câu trả lời dài hơn tiêu tốn nhiều token hơn, đồng nghĩa với việc tăng chi phí hoặc giới hạn dung lượng xử lý trong một phiên. Vì vậy chúng ta cần hiểu rõ hơn cách tính và xử lý token như sau<br>
&emsp; ✏️ Nếu không sử dụng các công cụ trên, bạn có thể ước tính số lượng token dựa trên độ dài văn bản:<br>
&emsp;&nbsp; 🔹 Tiếng Anh: Trung bình, 1 token tương đương khoảng 4 ký tự hoặc 0.75 từ.<br>
&emsp;&nbsp; 🔹 Tiếng Việt: Do đặc thù ngôn ngữ, 1 token có thể tương đương khoảng 3 ký tự.<br>
&emsp;&nbsp; 🔹 Tiếng Hàn: Trung bình 1 token ≈ 2 ký tự (do tiếng Hàn sử dụng chữ Hangul có cấu trúc gọn hơn).<br>
&emsp;&emsp;Ví dụ:<br>
&emsp;&nbsp;&emsp; 🔹 Một đoạn văn bản tiếng Anh dài 100 từ có thể tương đương khoảng 75 token.<br>
<br>
💡 Tối ưu hóa token<br>
&emsp;&nbsp; ✔️ Giảm độ dài câu hỏi nếu không cần thiết.<br>
&emsp;&nbsp; ✔️ Yêu cầu câu trả lời ngắn gọn nếu cần tiết kiệm token.<br>
&emsp;&nbsp; ✔️ Sử dụng cú pháp đơn giản thay vì diễn đạt dài dòng.<br>
[Back to II. Tips](#iitips)

