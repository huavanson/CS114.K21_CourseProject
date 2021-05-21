# CS114_CourseProject
### BÀI TOÁN NHẬN DIỆN MỘT NGƯỜI CÓ ĐỘI MŨ BẢO HIỂM HAY KHÔNG

## Mô tả bài toán

Yêu cầu từ thực tế:  Theo số liệu thống kê của Ủy ban An toàn giao thông Quốc gia thì mỗi năm ở nước ta có hơn 8000 người chết vì tai nạn giao thông .
Trong đó , số người đi môtô xe máy gây tai nạn giao thông chiếm 60%, số người đi xe máy là nạn nhân tai nạn giao thông là 85% . Một thống kê khác cho 
thấy  đội mũ bảo hiểm giúp giảm 40% nguy cơ thương vong khi bị tai nạn giao thông. Do đó cần xây dựng một ứng dụng giám sát người tham gia giao thông 
có đội mũ hay không để có các biện pháp xử phạt và ngăn chặn việc tham gia giao thông không đội mũ bảo hiểm , giúp giảm được một phần thiệt hại do tai 
nạn giao thông gây ra .

+ Input: Hình ảnh một người đang tham gia giao thông bằng xe gắn máy .
+ Output: Cho biết người đó đang đội mũ hay không .

## Dữ liệu 
Data sẽ được thu thập theo các bước
* Quay video ở định dạng 4k 30 fps để đảm bảo hình  ảnh trích xuất ra có chất lượng chấp nhận được .
* Trích xuất hình ảnh từ video bằng app Frame Grabber , ứng dụng này cho phép trích xuất tối đa 24 frame/s nhưn bọn mình chỉ lấy 
trung bình 3-5frame/s để đảm bảo có sự khác nhau về mặt góc độ  giữa những bức hình  .
* Crop bớt phần rìa để tập trung vào chủ thể là người đang tham gia giao thông bằng xe gắn máy .
* Hình ảnh sẽ được resize về kích thước 224 * 224 trước khi đưa vào trích xuất đặc trưng 
* ảnh sẽ được chia train/test theo tỉ lệ 8/2 



### Nếu không thể view code ở đây, hãy truy cập : https://nbviewer.jupyter.org/github/huavanson/ML_Project/blob/master/ML_helmet_rec.ipynb
