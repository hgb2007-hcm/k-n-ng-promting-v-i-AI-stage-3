Dưới đây là mẫu Prompt được thiết kế chuẩn theo khung **CREATE** (Character, Request, Examples, Adjustments, Type of output, Extras), đáp ứng đầy đủ các ràng buộc dữ liệu, yêu cầu nghiệp vụ và định dạng đầu ra của đề bài:

---

### Prompt hoàn chỉnh (Khung CREATE)

> **[C - Character / Vai trò]**
> Hãy đóng vai một chuyên gia cố vấn học tập và quản lý thời gian cho sinh viên đại học, có kinh nghiệm khắc phục thói quen trì hoãn và tối ưu hóa hiệu suất tự học.
> **[R - Request / Yêu cầu]**
> Dựa trên bối cảnh và các ràng buộc bên dưới, hãy phân tích quỹ thời gian và xây dựng cho tôi một kế hoạch học tập chi tiết trong 7 ngày (từ Thứ Hai đến Chủ Nhật):
> * **Bối cảnh:** Tôi là sinh viên năm nhất thường xuyên trì hoãn, chưa biết cách phân bổ thời gian giữa việc học trên lớp, tự học và giải trí.
> * **Lịch cố định:** Học trên lớp từ Thứ Hai đến Thứ Sáu, khung giờ 7h30–11h30.
> * **Yêu cầu nghiệp vụ:** Phân bổ thời gian tự học vào buổi chiều và buổi tối; ưu tiên các môn học có nhiều bài tập; đảm bảo sự cân bằng giữa học tập, nghỉ ngơi và giải trí.
> 
> 
> **[E - Examples / Ví dụ mẫu]**
> Định dạng các dòng trong bảng cần ngắn gọn, rõ ràng theo mẫu sau:
> * Ngày: Thứ Hai | Thời gian: 14h00–16h00 | Hoạt động: Tự học môn Giải tích (làm bài tập chương 1) | Mục tiêu: Hoàn thành 80% bài tập được giao.
> 
> 
> **[A - Adjustments / Điều chỉnh & Ràng buộc]**
> Kế hoạch bắt buộc phải tuân thủ nghiêm ngặt các quy tắc sau:
> * Không xếp lịch học (bao gồm cả trên lớp và tự học) kéo dài quá 3 giờ liên tục.
> * Phải bố trí các khoảng thời gian nghỉ ngơi xen kẽ giữa các ca học.
> * Mỗi ngày đều phải có ít nhất 1 giờ dành cho hoạt động giải trí cá nhân.
> * Tận dụng hợp lý thời gian trống vào Thứ Bảy và Chủ Nhật để ôn tập hoặc giải quyết các bài tập lớn.
> 
> 
> **[T - Type of output / Định dạng đầu ra]**
> Trình bày kết quả dưới dạng **Bảng Markdown** gồm đầy đủ 7 ngày (Thứ Hai đến Chủ Nhật) với đúng 4 cột theo thứ tự: `Ngày`, `Thời gian`, `Hoạt động`, `Mục tiêu`.
> **[E - Extras / Yêu cầu bổ sung]**
> * Ngay bên dưới bảng kế hoạch, hãy viết thêm một phần nhận xét ngắn gọn (dưới dạng gạch đầu dòng, tối đa 4 ý) đánh giá về tính hợp lý và khả thi của lịch trình này.
> * **Lưu ý quan trọng:** Tuyệt đối không trình bày nội dung dưới dạng các đoạn văn dài dòng; chỉ sử dụng bảng và các ý gạch đầu dòng súc tích.
> 
> 

---

### Bảng ánh xạ kiểm tra các tiêu chí (Dùng để đối chiếu)

| Thành phần khung CREATE | Nội dung đề bài đã được tích hợp |
| --- | --- |
| **C**haracter | Định hình AI làm cố vấn học tập chuyên trị bệnh trì hoãn cho sinh viên năm nhất. |
| **R**equest | Phân tích thời gian, lập lịch 7 ngày, ưu tiên môn nhiều bài tập, cân bằng học – chơi. |
| **E**xamples | Cung cấp 1 dòng mẫu chuẩn để AI hiểu rõ độ chi tiết của cột *Hoạt động* và *Mục tiêu*. |
| **A**djustments | Ràng buộc lịch trên lớp (T2–T6, 7h30–11h30), học chiều/tối, không quá 3h liên tục, có nghỉ ngơi, tối thiểu 1h giải trí/ngày. |
| **T**ype of output | Bảng Markdown 7 ngày với đúng 4 cột: `Ngày`, `Thời gian`, `Hoạt động`, `Mục tiêu`. |
| **E**xtras | Thêm phần nhận xét ngắn gọn về tính hợp lý và cấm viết đoạn văn dài. |