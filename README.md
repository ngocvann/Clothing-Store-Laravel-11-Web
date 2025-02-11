Clothing Store Website (Laravel 11)

📖 Giới thiệu

Dự án "Clothing Store Website" là một ứng dụng web quản lý cửa hàng thời trang được xây dựng bằng PHP Laravel 11. Mục tiêu của dự án là cung cấp nền tảng cho khách hàng có thể duyệt sản phẩm, đặt hàng trực tuyến và quản trị viên quản lý hoạt động kinh doanh.

🚀 Chức năng chính

Người dùng (Customer)

Xem danh sách sản phẩm theo danh mục.

Tìm kiếm sản phẩm theo từ khóa.

Thêm sản phẩm vào giỏ hàng.

Đặt hàng và quản lý lịch sử đơn hàng.

Đăng ký, đăng nhập và quản lý thông tin cá nhân.

Quản trị viên (Admin)

Quản lý tài khoản khách hàng.

Thêm, sửa, xóa sản phẩm.

Quản lý danh mục sản phẩm.

Quản lý đơn hàng và trạng thái đơn hàng.

Quản lý khuyến mãi và mã giảm giá.

🛠️ Công nghệ sử dụng

Ngôn ngữ lập trình: PHP 8.x

Framework: Laravel 11

Frontend: HTML, CSS, Bootstrap 5, JavaScript

Cơ sở dữ liệu: MySQL

Quản lý phiên bản: Git, GitHub

🏗️ Cấu trúc dự án

app/Models: Chứa các model cho cơ sở dữ liệu.

resources/views: Chứa các file giao diện Blade.

routes/web.php: Định nghĩa các route cho ứng dụng.

public/: Thư mục chứa các tài nguyên công khai như hình ảnh và CSS.

⚙️ Cách chạy dự án

Bước 1: Clone repository

git clone https://github.com/ngocvann/Clothing-Store-Laravel-11-Web.git
cd Clothing-Store-Laravel-11-Web

Bước 2: Cài đặt các package

composer install

Bước 3: Cấu hình file .env

Sao chép file .env.example thành .env

Cập nhật thông tin kết nối cơ sở dữ liệu

Bước 4: Tạo key ứng dụng

php artisan key:generate

Bước 5: Chạy migration và seed dữ liệu (nếu có)

php artisan migrate

Bước 6: Khởi động server

php artisan serve

Truy cập ứng dụng tại http://localhost:8000

🧑‍💻 Đóng góp

Rất hoan nghênh mọi ý kiến đóng góp từ cộng đồng để phát triển dự án tốt hơn. Hãy tạo pull request hoặc issue để thảo luận.

📜 Giấy phép

Dự án này được phát hành dưới giấy phép MIT.

