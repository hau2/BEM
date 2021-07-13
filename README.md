BEM: là tiêu chuẩn đặt tên class khi viết css
## Ý nghĩa:
- Viết tắt của: Block Element Modifier
- Block: Khối
- Element: Thành phần trong khối
- Modifier: Bổ sung ý nghĩa cho 'Block' hoặc 'Element'

## Tại sao phải dùng BEM ?
- Mỗi người đặt một kiểu
- Members đặt class trùng nhau, CSS đè lên nhau

## Cú pháp
- .block
- .block__element

- .block--modifier
- .block__element--modifier

## Tính ứng dụng
- xây dựng layout trên website
- xây dựng thành phần trên website

## ưu điểm
- tính rõ ràng
- tái sữ dụng dể dàng
- giúp cả team làm việc với nhau dể dàng
- tính module, không lo CSS của class này ảnh hưởng lên CSS của class khác

## Nhược điểm
- tên class dài
- một số người cho là xấu

## Khi nào dùng BEM kà phù hợp
- dự án nhiều member
- dự án lớn, số lượng page nhiều hoặc số lượng các thành phần trên giao diện nhiều

## Thực hành
- làm button
- làm mesage
- làm 1 thành phần trên website
