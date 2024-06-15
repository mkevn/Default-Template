# Cảm biến siêu âm MKE-S01 Ultrasonic Distance Sensor

## Giới thiệu

Mạch led đơn MKE-M01 10mm single LED module sử dụng loại LED kích thước lớn 10mm giúp bạn dễ dàng ứng dụng trong các mô hình xe, trang trí,..., mạch gồm có 4 phiên bản với các màu sắc: Trắng, Xanh lá, Vàng, Đỏ.

Mạch led đơn MKE-M01 10mm single LED module thuộc hệ sinh thái phần cứng Robotics MakerEdu nên có thể sử dụng trực tiếp an toàn với các mạch điều khiển trung tâm ở cả hai mức điện áp 3.3VDC và 5VDC như: Arduino, Raspberry Pi, Jetson Nano, Micro:bit,....với chuẩn kết nối Connector XH2.54 thông dụng.

## Thông số kỹ thuật

- Điện áp hoạt động: 5VDC
- Chuẩn giao tiếp: Digital
- Điện áp giao tiếp: TTL 3.3VDC/5VDC
- Có 4 phiên bản màu sắc: Trắng , Xanh Lá, Vàng, Đỏ.
- Sử dụng LED kích thước 10mm.
- Tích hợp Transistor giúp giảm dòng tiêu thụ và bảo vệ các chân GPIO của mạch xử lý.
- Sử dụng trực tiếp an toàn với các board mạch giao tiếp ở cả hai mức điện áp 3.3VDC và 5VDC như: Arduino, Raspberry Pi, Jetson Nano, Micro:bit,....
- Bổ sung thêm các thiết kế ổn định, chống nhiễu.
- Chuẩn kết nối: connector XH2.54 3Pins
- Thuộc hệ sinh thái phần cứng Robotics MakerEdu, tương thích tốt nhất khi sử dụng với các [mạch điều khiển trung tâm của MakerEdu và MakerEdu Shield.](https://wiki.makerlab.vn/index.php/MakerEdu)

## Hình ảnh sản phẩm

![MKE_S01_Ultrasonic](/image/MKE_M01_Single_Led_01.jpg)

![MKE_S01_Ultrasonic](/image/MKE_M01_Single_Led_02.jpg)

## Kích thước sản phẩm

![MKE_S01_Ultrasonic](/image/MKE_M01_Single_Led_03.jpg)

## Các chân tín hiệu

- GND:	Chân cấp nguồn âm 0VDC
- 5V:	Chân cấp nguồn dương 5VDC
- SIG:	Chân tín hiệu Digital In

Digital In: 
- TTL HIGH: Hoạt động (On)
- TTL LOW:  Không hoạt động (Off)

## Hướng dẫn sử dụng

### Các thiết bị sử dụng trong bài hướng dẫn:

#### Arduino:
- [Mạch Vietduino Uno (Arduino Uno Compatible)](https://github.com/makerlabvn/Vietduino-Uno)
- [Mạch MakerEdu Shield for Arduino](https://github.com/makerlabvn/MakerEdu-Shield-for-Arduino)
- [Mạch màn hình LCD1602 I2C Display Module](https://github.com/makerlabvn/MKE-M07-LCD1602-I2C-Display-Module)

#### mBlock:

- [Mạch MakerEdu Creator (Arduino Uno Compatible)](https://github.com/makerlabvn/MakerEdu-Creator)
- [Mạch màn hình LCD1602 I2C Display Module](https://github.com/makerlabvn/MKE-M07-LCD1602-I2C-Display-Module)

#### Micro:bit:

- Mạch Micro:bit V2 hoặc các phiên bản tương thích.
- [Mạch MakerEdu Shield for Micro:bit](https://github.com/makerlabvn/MakerEdu-Shield-for-Microbit)
- [Mạch màn hình LCD1602 I2C Display Module](https://github.com/makerlabvn/MKE-M07-LCD1602-I2C-Display-Module)

### Hướng dẫn sử dụng với Arduino (Code C)
- Tải và cài đặt [phần mềm Arduino tại đây.](https://www.arduino.cc/en/software)
- Trong Tools / Library Manager, tìm và cài đặt bộ thư viện tổng hợp "MAKERLABVN" by MakerLab.vn
- Mở chương trình mẫu tại File / Examples / MAKERLABVN / Sensor / MKE-M01_Single_Led hoặc [tải chương trình mẫu tại đây](https://github.com/thanhtam18/MKE-M01-Single-Led-10mm-Module/tree/main/arduino)
- Chọn board là Arduino Uno (mạch Vietduino Uno tương thích với Arduino Uno), chọn đúng cổng COM Port của mạch và tiến hành nạp chương trình.
- Kết nối mạch Vietduino Uno với MakerEdu Shield, kết nối mạch Led tại cổng [A3] và màn hình LCD vào cổng [I2C] trên MakerEdu Shield, cấp nguồn qua cổng USB của Vietduino Uno để thấy chương trình hoạt động.

### Hướng dẫn lập trình với mBlock (kéo thả khối)

- Tải và cài đặt phần mềm mBlock 5 ([Windows](https://www.mediafire.com/file/ma55iajd7glwmbo/%255BMakerLab.vn%255D_mBlock_V5.4.3_for_Windows.zip/file) / [Mac Intel](https://www.mediafire.com/file/pjfngy6d7ktb55f/%255BMakerLab.vn%255D_mBlock_V5.4.3_for_Mac_Intel.zip/file) / [Mac M1M2](https://www.mediafire.com/file/mfdkgpgnpa7uv2s/%255BMakerLab.vn%255D_mBlock_V5.4.3_for_Mac_M1M2.zip/file))
- Thêm Device "MakerEdu Creator" by MakerEduVN
- Thêm Extension "Upload Mode Broadcast" by mBlock Official
- Thêm Extension "MakerEdu Hardware" by MakerEduVN
- Mở [chương trình mẫu tại đây](https://github.com/thanhtam18/MKE-M01-Single-Led-10mm-Module/tree/main/mBlock5), kết nối MakerEdu Creator với máy tính và nạp chương trình.
- Kết nối mạch Led với cổng [A3] và màn hình LCD vào cổng [I2C] trên MakerEdu Creator, cấp nguồn qua cổng USB của MakerEdu Creator để thấy chương trình hoạt động.


### Hướng dẫn lập trình với Micro:bit (kéo thả khối)

- Khởi động phần mềm MakeCode theo hướng dẫn.
- Cài đặt Extension MakerEdu Hardware trên MadeCode theo đường link sau: [https://github.com/makerlabvn/MakerEdu_Hardware](https://github.com/makerlabvn/MakerEdu_Hardware)
- Mở [chương trình mẫu tại đây](https://github.com/thanhtam18/MKE-M01-Single-Led-10mm-Module/tree/main/microbit), kết nối Micro:bit với máy tính và nạp chương trình.
- Kết nối mạch Micro:bit với MakerEdu Shield, kết nối mạch Led tại cổng [P3] và màn hình LCD vào cổng [I2C] trên MakerEdu Shield, cấp nguồn qua cổng USB của MakerEdu Shield để thấy chương trình hoạt động.

## Hỗ trợ và liên hệ:

- Website: [https://www.makerlab.vn/](https://www.makerlab.vn/)
- Facebook: [https://www.facebook.com/makerlabvn](https://www.facebook.com/makerlabvn)

## Nhà phân phối

- Các bạn có thể mua sản phẩm tại các [nhà phân phối của MakerLab](https://www.makerlab.vn/nha-phan-phoi/).
