# Lộ trình học tập 8 học kỳ (Roadmap) - Ngành Khoa học Máy tính

> **Ghi chú:** Bản nháp v0 (Bước 1: Viết tại lớp trong 7 phút - đóng máy) đã được em lưu thành tệp `roadmap-v0.md` riêng biệt trong kho mã này và ghi nhận commit sớm hơn bản cuối.

---

## H1 · Hỏi (Bước 2: Hỏi AI khi chưa mở tài liệu)

- **Vai giao cho AI:** Cố vấn học tập.
- **Câu lệnh (Prompt) đã dùng:** *"Bạn là cố vấn học tập. Việc: Lập bảng tám học kỳ cho sinh viên ngành Khoa học máy tính, hệ đại học chính quy, Trường Đại học Công nghệ TP.HCM (HUTECH). Định dạng: mỗi học kỳ một bảng gồm mã học phần, tên học phần, số tín chỉ. Cuối mỗi học kỳ ghi tổng tín chỉ. Cuối cùng ghi tổng tín chỉ toàn khoá."*

**Ảnh chụp màn hình toàn bộ câu trả lời gốc của AI (có rõ ngày giờ):**

<img width="2048" height="1265" alt="1" src="https://github.com/user-attachments/assets/1d55720d-f054-4d5b-95bd-4b15decbf483" />
<img width="2048" height="1278" alt="2" src="https://github.com/user-attachments/assets/461273b4-240c-41ec-a322-e12b22e6d4cc" />
<img width="2048" height="1270" alt="3" src="https://github.com/user-attachments/assets/2f4364ae-3fd0-49f6-91be-c6bf262ee652" />
<img width="2048" height="1268" alt="4" src="https://github.com/user-attachments/assets/ef35effd-f35c-44f4-a985-a57c765cecf5" />

---

## H2 · Hoài (Bước 3: Chất vấn nguồn trước khi kiểm)

- **Câu hỏi tiếp theo em đặt ra:** *"Bạn lấy thông tin này từ nguồn nào? Cho tôi đường dẫn."*
- **Nguyên văn AI trả lời:** *"Tôi tổng hợp thông tin từ Website chính thức của Trường Đại học Công nghệ TP.HCM (HUTECH) tại địa chỉ hutech.edu.vn và các cổng thông tin tuyển sinh, đào tạo công khai của nhà trường. Tuy nhiên, tôi không thể truy cập trực tiếp các tệp PDF mã hóa hoặc đường dẫn nội bộ cụ thể tại thời điểm này."*
- **Nhận xét:** AI trả lời rất mập mờ, chỉ đưa ra địa chỉ trang chủ chung chung (`hutech.edu.vn`) chứ hoàn toàn không cung cấp được liên kết trực tiếp tới tệp Chương trình đào tạo chi tiết, chứng tỏ nó đang cố tình sinh dữ liệu giả.

---

## H3 · Học (Bước 4 & 5: Đối chiếu tài liệu thật và lập bảng 3 lỗi)

Sau khi chất vấn AI, em mới chính thức mở tệp Chương trình đào tạo ngành Khoa học máy tính thật (Quyết định 2574/QĐ-ĐKC). Làm "phép cộng 20 giây" và đối chiếu từng dòng, em bắt được 3 lỗi sau:

| 1. AI nói gì (Chép nguyên văn) | 2. Sự thật theo chương trình đào tạo | 3. Trích dẫn nguồn (Trang/Mục) | 4. Kiểu lỗi |
| :--- | :--- | :--- | :--- |
| "Tổng số tín chỉ tích lũy toàn khóa: 130 tín chỉ" | Tổng khối lượng kiến thức tích lũy toàn khóa chuẩn là 150 tín chỉ. Phép tính tổng của AI đã làm hụt mất 20 tín chỉ tốt nghiệp của sinh viên. | Trang 1, Mục "Tổng khối lượng kiến thức" | **Sai số liệu (Bắt bằng phép kiểm số học)** |
| "Mã học phần KHM203: Hệ thống số và vi xử lý (3 tín chỉ)" | Không có học phần nào có mã `KHM203` hay tên như vậy trong toàn bộ khung 62 học phần của ngành Khoa học máy tính HUTECH. | Trang 1–3, Danh mục các học phần bắt buộc | **Bịa tên học phần** |
| "Mã học phần KVA401: Khóa luận tốt nghiệp (10 tín chỉ)" | Tên, mã và khối lượng chuẩn là `COS4012: Đồ án tốt nghiệp Khoa học máy tính` với khối lượng đúng là 9 tín chỉ. | Trang 3, Mục II.2.3 (Nhóm 3: Đồ án tốt nghiệp) | **Suy diễn không căn cứ (Lấy từ trường khác)** |

---

## H4 · Hành (Bước 6: Tự lập bảng 8 học kỳ bằng tay)

Nhận thấy bảng của AI sai lệch cấu trúc, em tự tay giải bài toán xếp lịch 150 tín chỉ dựa trên CTĐT thật. Lấy **thời khóa biểu thực tế em đang học ở Học kỳ 1** làm mốc xuất phát, các học kỳ sau được bố trí tuân thủ tuyệt đối quy tắc tiên quyết và không dồn ép quá khối lượng an toàn (16-20 TC/kỳ):

### Học kỳ 1 (16 TC Tích lũy - Đang học thực tế)
| Mã HP | Tên học phần | Số TC | Tiên quyết |
| :--- | :--- | :---: | :--- |
| ENC120 | Anh ngữ 1 | 3 | Không |
| COS673 | Nhập môn ngành Khoa học máy tính | 3 | Không |
| SKL115 | Tư duy thiết kế dự án | 3 | Không |
| CMP1074 | Cơ sở lập trình | 3 | Không |
| MAT101 | Đại số tuyến tính | 3 | Không |
| CMP3075 | Thực hành cơ sở lập trình | 1 | Song hành |
| NDF108 | Quốc phòng, an ninh 1 | *(1)* | *(Không tích lũy)* |
* **Tổng HK1:** 16 TC | **Tích lũy:** 16/150 TC

### Học kỳ 2 (19 Tín chỉ)
| Mã HP | Tên học phần | Số TC | Tiên quyết |
| :--- | :--- | :---: | :--- |
| POS104 | Triết học Mác - Lênin | 3 | Không |
| ENC121 | Anh ngữ 2 | 3 | Anh ngữ 1 |
| MAT118 | Giải tích | 3 | Không |
| SKL116 | Đổi mới sáng tạo và tư duy khởi nghiệp | 3 | Tư duy TK dự án |
| CMP164 | Kỹ thuật lập trình | 3 | Cơ sở lập trình |
| COS135 | Nhập môn cơ sở dữ liệu | 3 | Không |
| CMP3014 | Thực hành lý thuyết đồ thị | 1 | Không |
| NDF109 | Quốc phòng, an ninh 2 | *(1)* | *(Không tích lũy)* |
| PHT304 | GDTC 1 (Bóng chuyền 1) | *(2)* | *(Không tích lũy)* |
* **Tổng HK2:** 19 TC | **Tích lũy:** 35/150 TC

### Học kỳ 3 (19 Tín chỉ)
| Mã HP | Tên học phần | Số TC | Tiên quyết |
| :--- | :--- | :---: | :--- |
| POS105 | Kinh tế chính trị Mác - Lênin | 2 | Triết học Mác-Lênin |
| ENC122 | Anh ngữ 3 | 3 | Anh ngữ 2 |
| MAT104 | Toán rời rạc | 3 | Không |
| CMP167 | Lập trình hướng đối tượng | 3 | Không |
| COS1002 | Các hệ quản trị cơ sở dữ liệu | 3 | Không |
| COS120 | Cấu trúc dữ liệu và giải thuật | 3 | Kỹ thuật lập trình |
| CMP365 | Thực hành kỹ thuật lập trình | 1 | Kỹ thuật lập trình |
| COS323 | Thực hành cơ sở dữ liệu | 1 | Nhập môn CSDL |
| NDF210 | Quốc phòng, an ninh 3 | *(1)* | *(Không tích lũy)* |
| PHT305 | GDTC 2 (Bóng chuyền 2) | *(2)* | *(Không tích lũy)* |
* **Tổng HK3:** 19 TC | **Tích lũy:** 54/150 TC

### Học kỳ 4 (20 Tín chỉ)
| Mã HP | Tên học phần | Số TC | Tiên quyết |
| :--- | :--- | :---: | :--- |
| POS106 | Chủ nghĩa xã hội khoa học | 2 | Kinh tế chính trị |
| ENC123 | Anh ngữ 4 | 3 | Anh ngữ 3 |
| MAT105 | Xác suất thống kê | 3 | Không |
| CMP172 | Mạng máy tính | 3 | Không |
| AIT1001 | Cơ sở trí tuệ nhân tạo | 3 | Không |
| AIT103 | Lập trình cho trí tuệ nhân tạo | 3 | Không |
| COS321 | Thực hành cấu trúc dữ liệu và giải thuật | 1 | CTDL & Giải thuật |
| CMP368 | Thực hành lập trình hướng đối tượng | 1 | Lập trình HĐT |
| COS324 | Thực hành quản trị cơ sở dữ liệu | 1 | Các hệ QTCSDL |
| NDF211 | Quốc phòng, an ninh 4 | *(1)* | *(Không tích lũy)* |
| PHT306 | GDTC 3 (Bóng chuyền 3) | *(1)* | *(Không tích lũy)* |
* **Tổng HK4:** 20 TC | **Tích lũy:** 74/150 TC

### Học kỳ 5 (19 Tín chỉ)
| Mã HP | Tên học phần | Số TC | Tiên quyết |
| :--- | :--- | :---: | :--- |
| POS103 | Tư tưởng Hồ Chí Minh | 2 | Không |
| ENS192 | Phát triển bền vững | 3 | Không |
| CMP1047 | Phân tích và trực quan dữ liệu | 3 | Không |
| CMP174 | Bảo mật thông tin | 3 | Lập trình HĐT |
| AIT104 | Máy học | 3 | Không |
| CMP170 | Lập trình trên môi trường Windows | 3 | Lập trình HĐT |
| CMP373 | Thực hành mạng máy tính | 1 | Mạng máy tính |
| AIT305 | Thực hành lập trình cho trí tuệ nhân tạo | 1 | Lập trình cho AI |
* **Tổng HK5:** 19 TC | **Tích lũy:** 93/150 TC

### Học kỳ 6 (20 Tín chỉ)
| Mã HP | Tên học phần | Số TC | Tiên quyết |
| :--- | :--- | :---: | :--- |
| POS107 | Lịch sử Đảng Cộng sản Việt Nam | 2 | Chủ nghĩa XHKH |
| LAW106 | Pháp luật đại cương | 3 | Không |
| CMP101 | Công nghệ phần mềm | 3 | Không |
| CMP177 | Lập trình trên thiết bị di động | 3 | Lập trình HĐT |
| COS129 | Điện toán đám mây | 3 | Không |
| AIT108 | Xử lý ảnh và ứng dụng | 3 | Không |
| AIT306 | Thực hành máy học | 1 | Máy học |
| CMP3055 | Thực hành phân tích và trực quan dữ liệu | 1 | Phân tích & TQ DL |
| CMP371 | Thực hành lập trình trên môi trường Windows | 1 | Lập trình Windows |
* **Tổng HK6:** 20 TC | **Tích lũy:** 113/150 TC

### Học kỳ 7 (18 Tín chỉ)
| Mã HP | Tên học phần | Số TC | Tiên quyết |
| :--- | :--- | :---: | :--- |
| COS158 | Lập trình devops | 3 | Lập trình HĐT |
| COS159 | Đồ họa ứng dụng trong khoa học máy tính | 3 | Không |
| CMP1020 | Học sâu | 3 | Không |
| AIT1002 | Nghệ thuật lập trình với hỗ trợ AI | 3 | Không |
| CMP1049 | Khai thác dữ liệu **(Tự chọn 1)** | 3 | Không |
| AIT307 | Thực hành xử lý ảnh và ứng dụng | 1 | Xử lý ảnh |
| CMP5089 | Thực tập điện toán đám mây | 1 | Điện toán đám mây |
| COS360 | Thực hành lập trình devops | 1 | Lập trình devops |
* **Tổng HK7:** 18 TC | **Tích lũy:** 131/150 TC

### Học kỳ 8 (19 Tín chỉ)
| Mã HP | Tên học phần | Số TC | Tiên quyết |
| :--- | :--- | :---: | :--- |
| COS1010 | Cơ sở công nghệ chuỗi khối | 3 | Không |
| COS464 | Đồ án chuyên ngành Khoa học máy tính | 3 | Không |
| COS5011 | Thực tập cơ sở ngành Khoa học máy tính | 3 | Không |
| COS570 | Thực tập tốt nghiệp ngành KHMT | 3 | Không |
| AIT1008 | Phân tích ảnh và thị giác máy tính **(Tự chọn 2)** | 3 | Không |
| AIT109 | Xử lý ngôn ngữ tự nhiên và ứng dụng **(Tự chọn 3)** | 3 | Không |
| AIT3007 | Thực hành nghệ thuật lập trình với hỗ trợ AI | 1 | Nghệ thuật LT AI |
* **Tổng HK8:** 19 TC | **Tổng tích lũy toàn khóa:** **150 TC**

---

## H4 · Hành (Bước 7: Viết đoạn 150 chữ kết nối nghề nghiệp)

Trong danh mục các học phần tự chọn thuộc nhóm Công nghệ Trí tuệ nhân tạo, em quyết định lựa chọn học phần **Phân tích ảnh và thị giác máy tính (AIT1008 - 3 Tín chỉ)** ở Học kỳ 8 để đưa vào lộ trình cá nhân. 

Lý do em chọn học phần này xuất phát trực tiếp từ mục tiêu nghề nghiệp đã xác định trong `career.md`: trở thành một **Kỹ sư AI / Học máy (AI/ML Engineer)**. Dù các môn học bắt buộc như *Cơ sở trí tuệ nhân tạo* hay *Máy học* đã trang bị nền tảng thuật toán và tư duy mô hình, nhưng *Phân tích ảnh và thị giác máy tính* mới là mảnh ghép giúp em đi sâu vào kỹ thuật xử lý dữ liệu phi cấu trúc hình ảnh/video thực tế. Kiến thức về xử lý ảnh, trích xuất đặc trưng và nhận diện đối tượng từ học phần này bổ trợ trực tiếp cho năng lực phát triển các ứng dụng AI thực chiến, giúp em hoàn thiện Dự án 3 trong CV và đáp ứng chính xác yêu cầu tuyển dụng khắt khe từ các doanh nghiệp công nghệ.
