# Student-Feedback-Analysis
Phân tích kết quả phản hồi của sinh viên về tư vấn tuyển sinh của trường đại học
- Student _Feedback_Analysis.ipynb : Phân tích và thống kê
- KHẢO-SÁT-ĐÁNH-GIÁ-CỦA-SINH-VIÊN-V-CÔNG-TÁC-TUYỂN-SINH-CỦA-TRƯỜNG-ĐẠI-HỌC.pdf : Bộ câu hỏi thu thập dữ liệu để phân tích
Mình đã đọc qua nội dung notebook **Student_Feedback_Analysis.ipynb**. Đây là project phân tích dữ liệu khảo sát phản hồi sinh viên từ file CSV. Mình viết sẵn bản **README.md** để bạn đưa lên GitHub:

## Giới thiệu

Dự án này thực hiện phân tích dữ liệu phản hồi của sinh viên thông qua khảo sát gồm **10 câu hỏi**:

* **5 câu đầu**: thuộc **Phần 1** (câu hỏi nhóm 1).
* **5 câu cuối**: thuộc **Phần 2** (câu hỏi nhóm 2).

Kết quả trả lời được mã hóa như sau:

* `1` → Đồng ý (**Tích cực**)
* `0` → Không ý kiến (**Trung lập**)
* `-1` → Không đồng ý (**Tiêu cực**)

Mục tiêu: Thống kê, trực quan hóa dữ liệu và phân tích mức độ hài lòng của sinh viên.

## Dữ liệu

* File dữ liệu gốc: **file.csv**
* Nội dung: Bảng kết quả khảo sát với các dòng là sinh viên và cột là câu hỏi.
* Các file đầu ra:

  * **Thongkedata.csv**: chứa kết quả thống kê từng câu hỏi.
  * Biểu đồ trực quan hóa phản hồi của sinh viên.

## Các bước thực hiện

1. **Đọc dữ liệu** từ `file.csv` bằng **Pandas**.
2. **Thống kê tổng quan**: số lượng câu hỏi, số người khảo sát.
3. **Thống kê chi tiết**: đếm số lượng phản hồi tích cực / trung lập / tiêu cực cho từng câu hỏi.
4. **Xuất kết quả** ra file `Thongkedata.csv`.
5. **Phân tích theo nhóm**: thống kê kết quả phần 1 và phần 2.
6. **Trực quan hóa** dữ liệu bằng **Matplotlib**.

## Công nghệ sử dụng

* Python 3.x
* Pandas
* Matplotlib
* CSV
