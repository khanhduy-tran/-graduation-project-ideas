# -graduation-project-ideas
Năm ý tưởng cực thú vị cho đồ án tốt nghiệp ngành CNTT
🌞Với các bạn sinh viên, nghĩ ra ý tưởng hay ho đã khó, xem xét ý tưởng đó có khả thi hay không, lựa chọn công nghệ để thực hiện còn khó hơn. Do vậy, trong bài này, mình sẽ gợi ý một số ý tưởng thú dzị, không quá khó mà lại hay, rất thích hợp để làm đồ án tốt nghiệp.
🌞Bên cạnh đó, mình cũng gợi ý luôn một số công nghệ mà các bạn có thể tìm hiểu và sử dụng cho đồ án nhé!
🌞Các đồ án này cần team khoảng 3-4 sinh viên làm trong 3-4 tháng kể cả viết document, nếu các bạn có ít người hơn thì cứ việc bỏ bớt chức năng ha.
✅𝟏. Hệ thống chuỗi cửa hàng kinh doanh(bán gì cũng được)
Hệ thống gồm một chuỗi các cửa hàng kinh doanh và một trung tâm chính. Mỗi cửa hàng sẽ có một cơ sở dữ liệu riêng, thực hiện đồng bộ dữ liệu 2 chiều giữa cửa hàng và trung tâm.
Chức năng chính:
● Quản lý (Thêm bớt xóa sửa dữ liệu)
● Đồng bộ hoá dữ liệu (giữa nhiều cửa hàng và trung tâm chính)
● Xuất báo cáo (Dưới dạng PDF, Excel)
Độ khó: 3/5 (1 là dễ nhất, 5 là khó nhất)
Công nghệ sử dụng: 
● WebForm hoặc WPF để làm phần mềm tại các trung tâm
● ASP. NET hoặc Java để làm web nhằm truy cập từ xa
● Microsoft SQL Server có hỗ trợ cơ chế đồng bộ
✅𝟐. Hệ thống giao thức ăn nhanh
Hệ thống giao thức ăn nhanh tương tự deliverynow. vn. Người dùng có thể đặt món ăn, theo dõi vị trí người bán, nhận thức ăn và thanh toán.
Chức năng chính:
● Bản web của người dùng: Xem món ăn và cửa hàng, đặt hàng, 
theo dõi nhân viên giao hàng thanh toán.
● Bản mobile của người dùng: Chức năng tương tự bản web, có 
thêm notify để báo người dùng khi đồ ăn gần đến nơi.
● Bản web của admin: Quản lý đơn hàng, báo cáo
Bản mobile của nhân viên giao hàng: Update vị trí của nhân viên 
để khách hàng theo dõi.
Độ khó: 4/5 (Hơi nhiều phần)
Công nghệ sử dụng: 
● Android SDK hoặc Swift để làm app (Có thể dùng ionic hoặc web 
native)
● Web thì dùng gì cũng được, có thể dùng Google Maps SDK để 
hiển thị thông tin
✅𝟑. Hệ thống chỉ đường xe buýt
Hệ thống định vị và chỉ đường tương tự Google Map, cho phép lựa chọn số trạm, đi bộ ít nhất, đi nhanh nhất, giá rẻ nhất v…v
Chức năng chính:
● Parse trang web của buyttphcm. com. vn để lấy thông tin các 
tuyến bus
● Phiên bản web: Tìm đường đi giữa 2 điểm thông qua tuyết bus
● Phiên bản mobile tương tự web, theo dõi vị trí người dùng
Độ khó: 4/5 (Thuật toán hơi khoai)
Công nghệ sử dụng:
● Android SDK hoặc Swift để làm app (Có thể dùng ionic hoặc 
React Native)
● Web thì dùng gì cũng được, có thể dùng Google Maps SDK để 
hiển thị thông tin
● HTML Parser (Selenium, HTML Agility Pack) để parse dữ liệu
✅𝟒. Web bán hàng thể thao
Một trang web bán hàng thể thao, lấy dữ liệu và sản phẩm từ nhiều trang khác bằng cách crawl. Hỗ trợ tracking đơn hàng, notify người dùng khi có sản phẩm mới v…v
Chức năng chính:
● Crawler để chôm dữ liệu từ các trang khác
● Quản lý order và đơn hàng. Thanh toán online
Độ khó: 2.5/5
Công nghệ sử dụng:
● Dùng ASP. NET hoặc Java để làm web
● HTML Parser (Selenium, HTML Agility Pack) để parse dữ liệu
● Dùng Twilio để gửi tin nhắn tới người dùng
✅𝟓. Điểm danh bằng nhận diện khuôn mặt và thiết bị di dộng
Hệ thống hỗ trợ điểm danh bằng cách… chụp hình. Giáo viên chụp hình để điểm danh, hệ thống sẽ nhận diện và biết sinh viên nào đi học.
Note: Đây là đồ án tốt nghiệp FPT của mình, được 9/10 điểm đấy nhé!
Chức năng chính:
● Phiên bản web: Cho phép quản lý học sinh, lớp học, lịch dạy của 
giáo viên. Đồng bộ lịch dạy lên Google Calendar và xuất report 
về tình trạng sinh viên đi học.
● Phiên bản di động: Giáo viên sử dụng để xem lịch học, chụp hình 
điểm danh. Ngoài ra còn có chức năng điểm danh manual, đồng 
bộ dữ liệu khi rớt mạng.
Độ khó: 4/5 (Dùng API sẵn thì chỉ còn 3/5. Ở đây mình có optimize thêm API và cách lưu ảnh để tăng độ chính xác).
Công nghệ sử dụng:
● ASP. NET MVC và Microsoft SQL Server.
● Android SDK và Swift để làm app di động.
● OpenCV, trên C# là EmguCV. Các bạn có thể dùng Microsoft 
Cognitive Service nếu muốn.
● EPPlus để xuất report dưới dạng file Excel.
