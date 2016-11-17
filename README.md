# Báo cáo học chuỗi

## 1.Khái niệm chuỗi kí tự
- là dãy kí tự đặt trong cặp dấu nháy kép ""
- mỗi ký tự của chuỗi được chứa trong một phần tử của mảng ( thực chất chuỗi ký tự là mọt mảng kiểu char)
- cú pháp khai báo chuối 
  ````````````````
  char ten[];
 ```````````````````````
 hoặc
 ````````````````````
 char *ten
 ```````````````````````
 
 ## 2. Thao tác trên chuỗi
 
 **Sử dụng các hàm chuẩn trong thư viện <string.h>**
 
 - **Hàm Strlen:**______`int strlen(char s[]);` __________________ trả lại độ dài chuỗi;
 - **Hàm strcpy:**______`strcpy(char chuoi1[],char chuoi2[]);`____ sao chép chuỗi 2 vào chuỗi 1
 - **Hàm strchr:**______`char*strchr(char s[],char c);`___________ tìm lần đầu tiên xuất hiện của c trong s, trả về địa chỉ của ký tự này
 - **Hàm strncpy:**_____`strncpy(char s[],s1[],int n);`___________ sao chép n ký trị trong s1 vào s, nếu độ dài của s1 không đủ n ký tự thì hàm điền thêm cái ký tự trắng vào chuỗi s
 - **Hàm strcat:**______`strcat(char s1[],char s2[]);`______________nối chuỗi s2 vào chuỗi s1, khi
 - **Hàm strncat:**_____`strncat(char s1[],char s2[], int n);`______nối n kí tự đâu tiên của s2 hco s1
 - **Hàm strstr:**______`char*strstr(char s1[], char s2[]);`________tìm vị trí xuất hiện đầu tiiên của chuôi s2 trong chuỗi s1
 - **Hàm strcmp:**______`int strcmp(char s1[],char s2[]);`_________so sánh 2 chuỗi s1 và s2.
     * nếu s1=s2,kết quả =0
     * nếu s1>s2, kết quả >0
     * nếu s1<s2, kết quả <0;
 - **Hàm  strncpm:**___` int strncpm(char s1[],char s2[],int n);`___so sánh n ký tự đầu tiên của ha chuỗi
 - **Hàm stricmp:** tương tự hàm strcmp nhưng không phân biệt chữ hoa và thường
 - **Hàm strincpm:** tương tự hàm strncpm nhưng không phân biệt hoa, thuonggừ
 - **Hàm strchar:**___`char *strchar( char s1[], c);`______________ tương tự strchr nhngư tìm kiếm từ cuối chuỗi.
 - **Hàm strlwr:**____`strlwr(char s[])`____________________________đổi toàn bộ chữ hoa sang chữ thường
 - **Hàm struppr:**___`struppr(char s[])`___________________________đổi toàn bộ chữ thường thành chữ hoa
 - **Hàm strset:**____`strset(char s[],char c);`____________________khởi đầu chuỗi s bằng ký tư c
 - **Hàm strnset:**___`strnset(char s[],char c,int n)`______________khỏi đầu cho n ký tự đầu tiên bằng ký tự c
 
## 3.Mảng và chuỗi ký tự
*sử dụng một mảng các biến con trỏ*
- *Cú pháp:* ` kieu *ten[size]`
- ví dụ:
``````````````
char *p[10];
````````````````
khai báo một mảng  con trỏ char dùng để lưu trữ địa chỉ của 10 chuỗi ký tự

