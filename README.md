# Django-tutorial
# em học được cách sử dụng Djano với kiểu xử lý của nó 
# cách tạo trang web có admin rộng hơn
# import from với em quen thuộc nên dễ học hiểu hơn 
# Biết những framwork như là django.contrib.staticfiles để quản lý tập tin tĩnh trong quá trình phát triển và triển khai ứng dụng
# Đăng ký admin qua superuser
# Tạo model Question đơn giản với việc thêm xóa sửa, nhưng nó có thêm DateTimeField, CharField để lưu lại đúng ngày và giờ mà mình thêm câu hỏi,truy vấn dữ liệu theo điều kiện thời gian
# Em học biết thêm những thao tác trên cơ sở dữ liệu sử dụng Django ORM tương tác với các model và dữ liệu trong cơ sở
# Sử dụng các phương thức tùy chỉnh trong model, kiểm tra xem phương thức tùy chỉnh was_published_recently() đã hoạt động đúng không
# Path 1: cách tạo 1 project của Django, tạo polls app cho việc quản lý chức năng của Question và choice, bao gồm: Models: Định nghĩa cấu trúc dữ liệu và các quan hệ giữa chúng.
# Views: tương tác với dữ liệu.
# Templates: Định dạng và hiển thị giao diện web.
# URLs:  URL và liên kết chúng với file views.
# Tests: Kiểm thử.
# Path2: biết thêm những framwork, và tạo model question và choice của Polls app, tạo các tập lệnh chứa thông tin về thay đổi cấu trúc cơ sở dữ liệu Polls bởi lệnh python manage.py makemigrations polls, thực hiện một loạt các thao tác trên cơ sở dữ liệu sử dụng Django ORM, import model Question và choice, tạo timezone truy vấn dữ liệu vào thời gian năm nào, chạy superuser để đăng ký tài khoản
# Path3: biết thêm class HttpResponse mà khi được trả về từ một view function, nó đại diện cho phản hồi HTTP được gửi từ máy chủ Django đến trình duyệt web, sử dụng hàm để hàm xử lý yêu cầu từ trình duyệt và trả về một HttpResponse. Và đưa ra 2 cách khác dùng render hoặc A shortcut: get_object_or_404 
# Path4: xử lý trang web polls, template_name: Xác định template được sử dụng để render trang index, get_queryset(): trả về danh sách các câu hỏi được sắp xếp theo thời gian xuất bản để hiển thị trên trang index, DetailView và ResultsView là hai class-based views. Vote một function-based view xử lý việc bỏ phiếu cho một câu hỏi
# Path5: tạo cuộc thử nghiệm để phát hiện lỗi với class QuestionModelTests trong file test.py, chạy test báo lỗi ở file và line bao nhiêu để ta đi fix bug nó 
# path6: thay đổi màu sắc của nền giao diện web trong file html
# Path7: tùy chỉnh biểu mẫu,thay thế model câu hỏi admin.site.register(Question), và tạo thêm nhiều sự lựa chọn của Choice trong polls app

# Hiện em chưa có câu hỏi gì hết :v 
