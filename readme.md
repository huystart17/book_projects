# Bắt buộc 
1. Dựng restful api cho books
2. Dựng api mượn sách
3. Viết test code (jest hoặc tương đương) 
4. Viết cronjob bắn webhook khi sách gần đến hạn phải trả (kịch bản báo người mượn trả sách) về https://webhook.site/ (vào đây lấy link) ![image](https://user-images.githubusercontent.com/16417051/156130421-7f19080d-d84f-496a-9d34-129b8000a173.png)
5. Tạo docker image
6. Tối ưu docker image


# Yêu cầu thêm 1: Dựng code base, đóng gói + xử lý hiệu năng
1. Sử dụng Koa js
2. Sử dụng bulljs để chạy job
3. sử dụng typescripts
4. Sử dụng jest để test cho các api đã viết
5. Sử dụng mongodb với mongoose
6. Dựng api tìm kiếm sách theo tên:
  - input "short everything" sẽ ra sách tên: A Short History of Nearly Everything
7. Sự dụng docker để đóng gói api
8. Sử dụng docker-compose để làm môi trường deploy : cấu hình cho app <500mb ram  và 1CPU. cấu hình cho db < 1g ram và 1 CPU
9. Api lấy danh sách sách, tìm kiếm cần < 100ms khi filter

# Yêu cầu thêm 2 : Xây dựng cơ chế nghiệp vụ và tư duy sản phẩm
1. Xây dựng cơ chế authen: đăng nhập, đăng ký
2. Xây dựng cơ chế phân quyền với 2 role chính: 1 thủ thư, 1 người dùng
3. Định nghĩa vai trò của thủ thư và của người dùng, xây dựng và thuyết minh tính năng
