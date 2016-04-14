## Hướng dẫn sử dụng git-GUI

#### 1. Tạo repo ở máy local và đồng bộ với github.com

##### Tạo mới repos

<img src="http://i.imgur.com/qZoINA0.png" />

- B1: Bấm vào "+" để tạo mới (Mặc định ở thẻ Create)
- B2: Đặt tên cho Repository
- B3: Bấm "Create Repository" để tạo

##### Thêm file vào repo

<img src="http://i.imgur.com/FEjPAE1.png" />

- B1: Kích chuột phải vào Repo vừa tạo, chọn Open in Explorer để mở nơi chứa Repo
- B2: Tạo một file README.md và biên soạn bằng trình Notepad, Notepad++,... như hình

<img src="http://i.imgur.com/yl1B7VY.png" />

##### Publish lên github

<img src="http://i.imgur.com/vwa1I2M.png" />

Sau khi biên soạn xong xuôi, chúng ta Publish lên git như sau: 

- B1: Bấm vào tên Repo mới tạo
- B2: Bấm vào thẻ Changes
- B3: Đặt viết vài từ ngắn ngọn vào ô Summary, biên tập vì lý do gì VD: sửa lỗi gì, thêm bớt gì,...
- B4: Bấm Commit để đẩy lên server github
- B5: Publish để công khai bài
	
<img src="http://i.imgur.com/wgciIxk.png" /> 

- B5.1: Chọn tài khoản mà chúng ta muốn up lên
- B5.2: Bấm vào Publish để hoàn tất

##### Sửa Repo

Sau khi sửa, viết thêm, hay xóa file ở trong Repo local. Khi muốn Sync với thư mục trên github, chúng ta chọn Repo vừa thay đổi và Sync dữ liệu. Cụ thể như sau:

<img src="http://i.imgur.com/QahNkPs.png" /> 

- B1: Bấm vào tên Repo cần Sync
- B2: Bấm vào thẻ Changes
- B3: Đặt viết vài từ ngắn ngọn vào ô Summary, biên tập vì lý do gì VD: sửa lỗi gì, thêm bớt gì,...
- B4: Bấm Sync
- Cuối cùng là Commit to master
- 5: Số thay đổi trong file

#### 2. Clone một Repository từ github về local

<img src="http://i.imgur.com/cBMiTTQ.png" />

Khởi động, git-GUI ta sẽ thấy như hình:

- B1: Bấm vào icon "+"
- B2: Chọn tài khoản
- B3: Chọn tab *Clone* để tải một repo về local
- B4: Chọn repo cần Clone
- B5: Bấm Clone **tên-repo**


####  3. Cách nhiều người up chung một Repo

- B1: Fork repo chung về github của mình

<img src="http://i.imgur.com/zGbBtiO.png" />

- B2: Vào git-GUI và Clone về local

<img src="http://i.imgur.com/dpi0cTI.png" />

- B3: Chỉnh sửa file ở local và Pull request lên Admin quản lý gói

<img src="http://i.imgur.com/ABaDDXi.png" />

Continue...