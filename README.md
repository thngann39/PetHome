# PetHome - Pet Services Appointment Mobile App

- **Introduction**: https://drive.google.com/file/d/1bAeQZVXL_CJKpWsTTtn89H1ZoE_ZK2fK/view?usp=sharing 

- **Figma**: https://www.figma.com/proto/JSbkBrYCZea1QBmePMs452/PetHome?node-id=0-1&t=x3KcITVjWclnoIst-1

- **Process Flows**: https://modeler.camunda.io/share/b406af2f-0ea9-401b-8405-93ee37a14edb

- **Other source**: https://drive.google.com/drive/folders/1n8pu4xyT_QiLKlY7e7Ne4_4Hr5PyWvWW?usp=sharing
---

**I. Overview**

**PetHome** là ứng dụng di động giúp đơn giản hóa quy trình đặt lịch hẹn chăm sóc thú cưng.

Ứng dụng sẽ hỗ trợ khách hàng:
- Đặt lịch và quản lý các dịch vụ chăm sóc thú cưng.
- Tạo hồ sơ riêng cho từng thú cưng.
- Xem lịch sử dịch vụ, theo dõi tình trạng sức khỏe.
- Nhận thông báo nhắc nhở lịch hẹn.
- Mua sắm đồ dùng thú cưng.

Ứng dụng  mang lại nhiều lợi ích thiết thực cho người dùng, giúp đơn giản hóa việc chăm sóc thú cưng một cách chủ động và thuận tiện. Thay vì phải gọi điện hoặc đến trực tiếp, người nuôi có thể dễ dàng đặt lịch, theo dõi lịch sử dịch vụ và nhận nhắc lịch tự động ngay trên điện thoại. Việc tích hợp đa dạng dịch vụ như khám bệnh, làm đẹp, tiêm phòng, trông giữ và mua sắm đồ dùng vào một nền tảng duy nhất giúp tiết kiệm thời gian, giảm nhầm lẫn và đảm bảo thú cưng được chăm sóc toàn diện, đều đặn. PetHome còn hỗ trợ nhiều loại thú cưng khác nhau, phù hợp với nhu cầu ngày càng đa dạng của người nuôi hiện đại.

---

**II. Responsibility:**
- Thu thập và phân tích nhu cầu người dùng, xác định các vấn đề trong quy trình đặt lịch chăm sóc thú cưng truyền thống.
- Phân tích quy trình hiện tại (As-Is), đánh dấu các Pain Points cụ thể và đề xuất quy trình cải tiến (To-Be).
- Xây dựng các tài liệu:
    - Context Diagram mô tả mối liên kết giữa hệ thống PetHome và các đối tượng.
    - Danh sách tính năng MVP xác định các chức năng cốt lõi cần có trong phiên bản đầu tiên, đảm bảo giải quyết các vấn đề chính của người dùng.
    - Feature List chi tiết hoá từng tính năng trong hệ thống.
    - Business Rules định nghĩa các quy tắc hoạt động cho từng chức năng.
- Thiết kế BPMN End-to-End cho các quy trình chính:
    - Đặt lịch dịch vụ
    - Đăng ký/Đăng nhập và xác thực OTP
    - Quản lý hồ sơ thú cưng
    - Mua hàng trong app
    - Thanh toán & check-in tại cơ sở
- Xây dựng ERD thể hiện mối quan hệ giữa các thực thể (thú cưng, chủ nuôi, nhân viên, lịch hẹn, phản hồi,...)
- Thiết kế prototype ứng dụng di động bằng Figma, mô phỏng luồng người dùng và trải nghiệm sử dụng.
