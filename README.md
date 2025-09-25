# lab06
Thiết kế chi tiết lớp &amp; kiến trúc ATM

Phạm vi
Thiết kế chi tiết lớp (Class Diagram) và kiến trúc gói (Package Diagram) cho ATM từ Use Case & Sequence

Quy ước/giả định
 Card có thể liên kết nhiều Account (1–N)

 
 Account ghi nhận nhiều Transaction (1–N)

 

 
 ATM tạo Transaction và thao tác qua Controller; nghiệp vụ thật ở BankService

 
 Trạng thái thẻ: ACTIVE/BLOCKED/EXPIRED (gợi ý enum)

 
 Loại giao dịch: WITHDRAW/DEPOSIT/TRANSFER

 
![class](https://github.com/n23dcpt013-wq/lab06/blob/main/atm%20class.png)

![package]()
