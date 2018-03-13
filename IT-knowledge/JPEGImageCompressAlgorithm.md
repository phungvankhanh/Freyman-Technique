# Thuật toán nén ảnh JPEG:  
**-Định nghĩa:** Là thuật toán dùng để giảm dung lượng của ảnh JPEG(ảnh tĩnh),
mà không ảnh hưởng quá nhiều đến nội dung của ảnh(phụ thuộc vào hệ số nén).  
**-Phương pháp nén ảnh:** từ dữ liệu ảnh đọc vào thành các số, dùng biến đổi cosin rời rạc kết hợp mã hóa Huffman
hoặc phương pháp Harra để làm các thành phần dư thừa bị biến mất.  

## Liên hệ:  
-Hình dung 1 cái hộp bên trong chứa các đồ đạc lộn xộn, thừa nhiều không gian trống
nhưng không cho thêm được nữa. Giờ ta nén nó tức ta giảm độ dư thừa về không gian đi, sắp xếp 
ngăn nắp lại, như vậy thay vì hộp chỉ chứa được đồ đạc như trên thì giờ có thể thêm được nữa.
Như vậy, đồ đạc là những thứ giá trị ta không thay đổi chúng mà thay đổi không gian dư thừa xung quanh
để làm cho nơi chứa chúng cần ít thể tích hơn.  