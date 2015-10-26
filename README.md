# elasticsearch-for-careers
Build a vietnamese analyzer of ElasticSearch in careers category

Chúng tôi sử dụng thư viện VnTokenizer của thầy Lê Hồng Phương(http://mim.hus.vnu.edu.vn/phuonglh/softwares/vnTokenizer) xin cảm ơn sự đóng góp của thầy. và source code xây dựng tokenizer cho elasticsearch của Duy Đỗ.

Về mặt ý tưởng chúng tôi sẽ:
1. Xây dựng một từ điển các danh từ, cụm danh dùng cho việc tìm kiếm công việc. Để xây dựng bộ từ điểm này sẽ được tối ưu hóa của bộ phận xây dung nội dung. có thể sữ dụng tất cả tag skills vietnamworks đang có.

2. Xây dựng 1 Tokenizer cho elasticsearch dùng thực hiện index nội dung theo từ điển tiếng việt & từ điển xây dựng ở bước một

3. Xây dựng một hệ thống tag tự động để chuyển tất cả các filter(thuộc tính của job ở dạnh ID như ngành nghề, khu vực....) thàng tag nội dung theo các bộ bussiness rule định sẵn.

4. Xây dựng tokenizer đánh giá score của một cụm từ keyword mà người dùng input.

5. Xây dựng tokenizer để thực hiện phân tách nội dung của một Job và từ các token này chuyển thành các tag.

