#Hướng dẫn lắp và cài đặt Repeater TP-Link TL-WR740 thu phát sóng

Tài liệu phục vụ cho nhân viên đi lắp đặt giàn thủy canh

__Bước 1: Lắp đặt TP-Link TL-WR640N__

- Lắp đặt ở vị trí thoáng mát, tránh cấc vật dụng bằng gỗ, nhôm làm suy giảm tín hiệu wifi
- Tránh đặt ở vị trí quá nóng, ẩm ước hoạt trên các thiết bị điện tử khác.
- Cắm apdater nguồn cho TP-Link WR740N, xem có nút on/off phía sau thì bấm mở nguồn cho TP-Link
- Cắm dây mạng từ máy tính tới cổng LAN để cấu hình cho router.

__Bước 2: Reset về cấu hình mặc định:__

Bấm giữ nút đen nhỏ reset phía sau TP-Link WR740 đến khi có hiện tượng tất cả các đèn đều nháy sáng rồi thả ra

__Bước 3: Cài đặt router ở chế độ repeater__

- Mở trình duyệt WEB (chorme, firefox, IE gì đó)
- Nhập vào 192.168.1.1
- Nhập User Name và Password đều là admin

![image1](/img/wifi/img1.png)

Đầu tiên click vào Wireless chọ Wireless Settings để cài đặt các thông số về wifi

Làm theo các bước như hình sau:

![image2](/img/wifi/img2.png)

B1: Đặt tên mạng wifi của Repeater (tên không được trùng với con wifi phát, tên không nên có khoảng trắng và các ký tự đặc biệt)

B2: Check vào Enable WDS ridging để cho phép TP-Link hoạt động ở chế độ Repeater.

B3: Nhấn vào nút Survey để dò tìm mạng wifi cần kết nối để repeater.

![image3](/img/wifi/img3.png)

rồi chọn mạng wifi cần kết nối

B4: Chọn đúng dạng mã hóa của con wifi phát xem ở hình 3. 

DVES_VP có kiểu WPA-PSK/WPA2-PSK thì chọn giống vậy

B5: Nhập password của con wifi phát (DVES_VP)

B6: Nhấn vào nút save

B7: Click chọn qua trang kế tiếp Wireless Sercurity

![image4](/img/wifi/img4.png)

B1: Click vào WPA/WPA2-Personal (Recommended)

B2: kiểu mã hóa, thông thường chọn giống hình WPA2-PSK, AES, sau đó nhập password cho con Repeater. vd: dongvietdves

B3: Nhấn vào nút save

Tiếp theo click chọn DHCP, chọn DHCP Settings.

![image5](/img/wifi/img5.png)

B1: Ở trang này chỉ cần chọn Disable DHCP Server

B2: Nhấn nút Save 

Đến đây là xong 99% rồi đấy

![image6](/img/wifi/img6.png)

Click vào chỗ __click here__ để khởi động lại TP_Link

![image7](/img/wifi/img7.png)

Khởi động xong thì xong rồi đó, kiểm tra xem có wifi của REPEATER chưa.

![image8](/img/wifi/img8.png)

Đã có wifi phát ra từ con router REPEATER mình vừa cấu hình rồi đó. Kết nối con Greenbot vào đây thôi.