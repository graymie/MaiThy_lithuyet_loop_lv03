#MaiThy_lithuyet_loop_lv03
#    *Loop*
## *Câu lệnh for*
### cú pháp:
- Cú pháp: `for ( khởi tạo; điều kiện ; biểu thức) việc_thực hiện;`
_Giải thích_:
Khởi tạo: là toán tử gán để tạo giá trị ban đầu cho biến điều khiển.
Điều kiện: biểu thức điều kiện để thực hiện vòng lặp.
Biểu thức: biểu thức tăng giá trị của biến điều khiển của vòng lặp.
ví dụ :
![hình ảnh](https://gc0904g6.files.wordpress.com/2014/02/12345678.jpg?w=500)

## *Câu lệnh while*
### cú pháp: ` while ( điều kiện) các lệnh cần lặp;`
### nguyên tắc
![nguyentac](http://www.nguyenvanquan7826.com/wp-content/uploads/2014/12/for.png)

vd:
![VD2](https://gc0904g6.files.wordpress.com/2014/02/taitai.jpg)
![vd3](https://gc0904g6.files.wordpress.com/2014/02/123321.jpg)

## *Câu lệnh do while:*
### Cú pháp : `do lệnh 1 ; while ( biểu thức 1 ) ;`
### nguyên tắc:
![nguyentac2](http://www.nguyenvanquan7826.com/wp-content/uploads/2014/12/do-while.png)
vd:(
  /#include <stdio.h>
  
 int main(){
 
    do {
        printf("khoi lenh duoc thuc hien\n");
    } while(5 > 8);
     
    return 0;
}


*chú ý*: : vòng lặp while thì có thể không thực hiện lệnh nào nếu ngay từ ban đầu biểu thức sai, còn lệnh do while thì sẽ thực hiện lệnh ít nhất 1 lần dù biểu thức có sai ngay từ đầu.

