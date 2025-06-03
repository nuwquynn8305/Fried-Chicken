
# Fried Chicken Shop - Website Bán Gà Rán

> Dự án xây dựng website bán gà rán online với các chức năng như xem menu, đặt món, thanh toán, quản lý đơn hàng và người dùng.
## Tác Giả 
- Tên : Đinh Thị NHư Quỳnh
- Github :  https://github.com/nuwquynn8305
## Mục lục

- [Giới thiệu](#giới-thiệu)
- [Tính năng](#tính-năng)
- [Công nghệ sử dụng](#công-nghệ-sử-dụng)
- [Cài đặt](#cài-đặt)
- [Cấu trúc thư mục](#cấu-trúc-thư-mục)
- [Hướng dẫn sử dụng](#hướng-dẫn-sử-dụng)
- [Ảnh minh họa](#ảnh-minh-họa)
- [Phát triển thêm](#phát-triển-thêm)
- [Tác giả](#tác-giả)

## Giới thiệu

Đây là dự án web bán hàng chuyên về gà rán, cho phép người dùng:
- Xem danh sách món ăn
- Đặt món trực tuyến
- Theo dõi đơn hàng
- Thanh toán nhanh chóng

Ngoài ra, admin có thể:
- Thêm / sửa / xóa món ăn
- Quản lý đơn hàng và người dùng

## Tính năng

### Người dùng
- Xem menu các món gà rán
- Tìm kiếm món ăn theo tên, giá, loại
- Thêm vào giỏ hàng và đặt món
- Thanh toán đơn hàng
- Xem lịch sử đơn hàng

### Admin
- Quản lý sản phẩm
- Quản lý đơn hàng
- Quản lý người dùng
- Thống kê doanh thu

## Công nghệ sử dụng

| Công nghệ        | Mục đích                             |
|------------------|--------------------------------------|
| React.js         | Frontend                            |
| Tailwind CSS     | Thiết kế giao diện đẹp và responsive |
| Node.js + Express| Backend API                         |
| MongoDB          | Cơ sở dữ liệu                        |
| JWT              | Xác thực người dùng                 |
| Mongoose         | ORM cho MongoDB                     |
| Cloudinary       | Upload ảnh món ăn                   |

## Cài đặt

```bash
# Clone dự án
git clone https://github.com/nuwquynn8305/Fried-Chicken.git
cd Fried-Chicken

# Cài đặt client
cd client
npm install

# Cài đặt server
cd ../server
npm install

# Tạo file .env trong thư mục server
cp .env.example .env

# Chạy server
npm run dev

# Chạy client
cd ../client
npm run dev
