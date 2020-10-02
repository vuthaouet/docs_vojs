#Quản lý

1. [Các tạp chí lưu trữ](administration#hosted-journals)
1. [Chức năng quản trị](administration#admin-functions)

Quản trị trang web được giới hạn cho người dùng có toàn quyền hệ thống. Các nhiệm vụ quản trị không thường xuyên và có thể được thực hiện bởi người quản lý tạp chí, biên tập viên cấp cao hoặc một quản trị viên chuyên trách của trang web.
## <a name="hosted-journals"></a>Các tạp chí lưu trữ

Thêm, chỉnh sửa hoặc xóa các tạp chí được lưu trữ trên cài đặt này. Sẽ chỉ có một tạp chí trong hầu hết các trường hợp, nhưng bạn có thể lưu trữ nhiều tạp chí với một cài đặt duy nhất.

Quản trị viên, người quản lý tạp chí hoặc biên tập viên cấp cao có thể truy cập ** Trình hướng dẫn cài đặt ** cho mỗi tạp chí được lưu trữ, sẽ hướng dẫn bạn qua các bước thiết lập tạp chí cơ bản. Chúng bao gồm thiết lập tiêu đề, chi tiết liên hệ, giao diện trang web, thông số gửi, chi tiết lập chỉ mục và người dùng.

## <a name="admin-functions"></a>Chức năng quản trị

Một số chức năng quản trị có sẵn trong khu vực quản trị trang web. Những điều này nên được sử dụng một cách thận trọng bởi các quản trị viên kỹ thuật. Sử dụng không đúng cách có thể dẫn đến kết quả không mong muốn.

### Thông tin hệ thống

Thông tin chi tiết về phiên bản phần mềm và cấu hình máy chủ.

### Expire User Sessions

Liên kết này sẽ đăng xuất tất cả người dùng ra khỏi hệ thống ngay lập tức. Điều này có thể hữu ích ngay trước khi tiến hành nâng cấp phần mềm.

### Xóa bộ nhớ cache dữ liệu

Xóa tất cả dữ liệu đã lưu trong bộ nhớ cache, bao gồm thông tin ngôn ngữ, bộ nhớ cache trợ giúp và bộ nhớ cache tìm kiếm.

### Xóa bộ nhớ đệm mẫu

Xóa tất cả các phiên bản đã lưu trong bộ nhớ cache của các mẫu HTML. Chức năng này có thể hữu ích để buộc tải lại các mẫu sau khi các tùy chỉnh đã được thực hiện.

### Xóa nhật ký thực thi tác vụ đã lên lịch

Loại bỏ các tệp nhật ký được tạo tự động bởi một số tác vụ bảo trì theo lịch trình, chẳng hạn như xử lý số liệu thống kê.