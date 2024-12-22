# PiMA_Challenge_Price_Change_Prediction
This is my code for PiMA Challenge 2024, as a part of Mathematics Modelling course. My team focused on problem 3.2. 

1.Thể lệ
1. Trong thử thách này, các đội cần xây dựng mô hình toán học và làm video ngắn thuyết
trình về mô hình của mình. Các đội thi sẽ chọn đúng 1 trong 3 đề do PiMA đưa ra.
Xem đề chi tiết tại Mục 3.
• Đề A: Vị trí mở cửa hàng tiện lợi
• Đề B: Biến động thị trường
• Đề C: Phân bố xe buýt trên các tuyến
2. Thời gian: 30/11/2024 - 21/12/2024
3. Mỗi đội thi từ 1-6 thành viên. Khi nộp bài đội sẽ thông báo lại tên nhóm và thông tin
thành viên.
Lưu ý: Mọi thành viên bắt buộc phải người tham gia khóa học này.
5. Mentor không hỗ trợ trong quá trình các nhóm thực hiện thử thách.
6. Các đội thi tự do chọn hình thức trình bày bài làm hoặc sử dụng Template của PiMA.
Slides thuyết trình là bắt buộc để tiện cho việc trình bày và theo dõi công thức toán.
7. Ngôn ngữ trình bày: Tiếng Việt
8. Video trình bày không quá 6 phút, trong đó đội thi không cần phải đề cập lại những
gì đã được nêu trong đề bài. Thời lượng dài hơn sẽ không được tính.
9. Video cần được tải lên YouTube với chế độ xem công khai. Đồng thời, các đội phải
nộp bài đúng hạn qua form sau: Team Video Submission - PiMA Modelling Challenge
2024
10. Hạn chót nộp bài làm: 23 giờ 59 phút, 21/12/2024
11. BTC không xử lý các trường hợp sai sót trong quá trình nộp bài từ các đội thi (quá
thời gian nộp, link YouTube lỗi, v.v.)
12. Sau khi công bố kết quả, BTC sẽ gửi riêng đánh giá và nhận xét đến các đội thi.

2.Tiêu chí đánh giá

• Bài thuyết trình của đội sẽ được đánh giá một cách tổng thể trên thang điểm 5: 1
(kém) đến 5 (xuất sắc). Điểm số sẽ dựa trên ba khía cạnh: Giả định hợp lý, công thức
toán chính xác, và khả năng giải quyết mô hình. Khía cạnh áp dụng vào dữ liệu thực tế
sẽ tính là điểm thưởng thêm.

• Điểm sẽ được tính trung bình từ tất cả các giám khảo và xếp hạng điểm từ cao đến
thấp. Giải thưởng sẽ được trao cho các đội theo ba hang mục: Xuất sắc (Outstanding),
Đáng khen (Meritorious), và Thành công (Successful).

Bài 3.2 – Biến động thị trường
Sau khi anh Trung đã chọn được vị trí mở cửa hàng tiện lợi cho PiMA Team Vietnam, anh phát hiện ra mặt hàng sổ tay ghi chú bán không chạy như dự tính. Anh Trung đã nhờ chị Thảo khảo sát thị trường thì phát hiện trong khu vực phường 4, quận 5 có một cửa hàng AMIP (Awesome Market for Interesting People) cũng bán mặt hàng sổ tay tương tự. Anh Long, chủ cửa hàng AMIP, cũng biết được rằng có cửa hàng của PiMA mới mở và đã nhờ chị Linh theo dõi giá cả của sổ tay mà cửa hàng PiMA bán ra. Sau mỗi ngày t, cả hai bên đều biết giá sổ tay mà cửa hàng PiMA và cửa hàng AMIP bán ra tương ứng là pt và at. Anh Trung và anh Long sẽ sử dụng thông tin này để quyết định giá bán của sổ tay vào ngày thứ t + 1, tương ứng là pt+1 và at+1. Hãy thiết kế các mô hình thể hiện sự thay đổi giá bán sổ tay theo thời gian. Trong những trường hợp nào bạn tìm được thì giá bán sổ tay tiến đến một giá trị không đổi?
