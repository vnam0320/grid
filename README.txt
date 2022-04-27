Đối tượng Grid:
class:
Grid: full width - chiếm hết chiều ngang của parent
Wide: chiều ngang TỐI ĐA 1200px 

Đối tượng Row:
vai trò: 
Chứa các columns, giúp các columns nằm theo chiều ngang
Khi tổng chiều ngang columns vượt quá kích thước Row, cho columns xuống dòng
Loại bỏ khoảng thừa do gutters tạo ra ở 2 phía

Đối tượng Column
Vai trò:
Chứa content, sử dụng padding để tạo gutters, col luôn là con trực tiếp của grid layout
-c-*: viết tắt của column - sử dụng trên moblie
-m-*: viết tắt của medium - sử dụng trên tablet
-l-*: viết tắt của large  - sử dụng trên PC