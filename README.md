### Các file được sử dụng trong dự án là mà nguồn cho các máy ảo EC2:
* file Userdata 1 được sử dụng cho web server 1
* file Userdata 2 được sử dụng cho web server 2
* file Cloud9-Script được sử dụng để thao tác trên Cloud9 terminal gồm các phần:
  - Script 1: Để tạo Mannager Secrets
  - Script 2: Dùng để lấy dữ liệu từ EC2 và chuyển vào RDS
  - Script 3: Để cài đặt loadtest và chạy LoadBalancer
