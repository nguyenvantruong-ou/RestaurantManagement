# RestaurantManagement
Website quản lý nhà hàng tiệc cưới, sử dụng Java Spring MVC, Hibernate, MySQL

- Mô hình: MVC 
- Ngôn ngữ:  Java, Javascript (Jquery), HTML, CSS, XML
- Framework, API, Library, Service: Spring MVC, Hibernate, Bootstrap 4, Cloudinary, ChartJs, JsPDF, Twillio, Sweet Alert
- Database: Mysql
- Nền tảng thanh toán online: Momo
- IDE, Công cụ: Intellij IDE, Vscode, MySQL Workbench, Git/GitHub, Trello, Diagrams.net

Chức năng: 
 - Phân quyền người dùng:
     + Admin: 
          + Quản lý người dùng
          + Quản lý sảng
          + Quản lý món ăn
          + Thống kê báo cáo
     + User: 
          + Đăng ký
          + Đăng nhập
          + Đặt tiệc
          + Tìm kiếm, sắp xếp sảnh
          + BÌnh luận, đánh giá sảnh
          + Phản hồi, khiếu nại
          + Thanh toán momo 
     + Nhân viên:
          + Thanh toán trực tiếp
          + Đặt tiệc
- Các tính năng thêm:
   + Xác thực bằng OTP thông qua gmail khi đăng kí tài khoản
   + Tích hợp Momo khi tiến hành thanh toán
   + Tích hợp gửi tin nhắn SMS thông qua Twillio API
   + Sử dụng Cloudinary service để lưu trữ hình ảnh của website
   + Sử dụng CharJs để hiển thị biểu đồ thống kê
   + Sử dụng JsPdf để xuất dữ liệu ra thành file pdf
   + Ngoài ra còn sử dụng một số tính năng khác: Sử dụng Province-Open API để lấy thông tin các tỉnh thành/quận huyện ở Việt Nam, Sweet Alert để hiển thị các thông báo.
