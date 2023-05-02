# Module 1

# Bootcamp Preparation

# Yêu cầu 1 ( If và switch case)

# Bài 1: Viết một chương trình để nhập lương nhân viên, tính thuế thu nhập và lương ròng (số tiền lương thực sự mà nhân viên đó nhận được). Với các thông số giả sử như sau (không theo luật lương, chỉ là con số giả sử để dễ tính toán):

# 20% thuế thu nhập nếu lương là 15 triệu. {#thuế-thu-nhập-nếu-lương-là-15-triệu. .unnumbered}

# 10% thuế thu nhập nếu lương từ 7 đến 15 triệu. {#thuế-thu-nhập-nếu-lương-từ-7-đến-15-triệu. .unnumbered}

# 5% thuế thu nhập nếu lương dưới 7 triệu {#thuế-thu-nhập-nếu-lương-dưới-7-triệu .unnumbered}

# Bài 2: Viết chương trình kiểm tra một ký tự trong bảng chữ cái tiếng anh là nguyên âm hay phụ âm. Ký tự là bất kỳ được nhập từ bàn phím. Các ký tự nguyên âm bao gồm: \'o\', \'u\', \'i\', \'a\', \'e\' hoặc \'O\', \'U\', \'I\', \'A\', \'E\' {#bài-2-viết-chương-trình-kiểm-tra-một-ký-tự-trong-bảng-chữ-cái-tiếng-anh-là-nguyên-âm-hay-phụ-âm.-ký-tự-là-bất-kỳ-được-nhập-từ-bàn-phím.-các-ký-tự-nguyên-âm-bao-gồm-o-u-i-a-e-hoặc-o-u-i-a-e .unnumbered}

# Yêu cầu 2 ( Loop )

# Bài 1: Vẽ tam giác vuông cân rỗng có chiều cao h. Ví dụ: h = 5 {#bài-1-vẽ-tam-giác-vuông-cân-rỗng-có-chiều-cao-h.-ví-dụ-h-5 .unnumbered}

# \* {#section .unnumbered}

# \* \* {#section-1 .unnumbered}

# \* \* {#section-2 .unnumbered}

# \* \* {#section-3 .unnumbered}

# \* \* \* \* \* {#section-4 .unnumbered}

# Bài 2: Vẽ tam giác cân đặc có chiều cao h do người dùng nhập vào. Ví dụ: h = 5 {#bài-2-vẽ-tam-giác-cân-đặc-có-chiều-cao-h-do-người-dùng-nhập-vào.-ví-dụ-h-5 .unnumbered}

#   {#section-5 .unnumbered}

#  \* {#section-6 .unnumbered}

#  \* \* \* {#section-7 .unnumbered}

#  \* \* \* \* \* {#section-8 .unnumbered}

#  \* \* \* \* \* \* \* {#section-9 .unnumbered}

# \* \* \* \* \* \* \* \* \* {#section-10 .unnumbered}

# Bài 3: Vẽ tam giác cân rỗng có chiều cao h do người dùng nhập vào. Ví dụ: h = 5 {#bài-3-vẽ-tam-giác-cân-rỗng-có-chiều-cao-h-do-người-dùng-nhập-vào.-ví-dụ-h-5 .unnumbered}

#  \* {#section-11 .unnumbered}

#  \* \* {#section-12 .unnumbered}

#  \* \* {#section-13 .unnumbered}

#  \* \* {#section-14 .unnumbered}

#  \* \* \* \* \* \* \* \* \* {#section-15 .unnumbered}

# Yêu cầu 3 (Mảng và Loop)

# Bài 1: Cho mảng a chỉ chứa các số nguyên {#bài-1-cho-mảng-a-chỉ-chứa-các-số-nguyên .unnumbered}

# Xây dựng mảng b là prefix sums của mảng a cụ thể theo công thức: {#xây-dựng-mảng-b-là-prefix-sums-của-mảng-a-cụ-thể-theo-công-thức .unnumbered}

#  b\[0\] = a\[0\] {#b0-a0 .unnumbered}

#  b\[1\] = a\[0\] + a\[1\] {#b1-a0-a1 .unnumbered}

#  b\[2\] = a\[0\] + a\[1\] + a\[2\] {#b2-a0-a1-a2 .unnumbered}

#  \... {#section-16 .unnumbered}

#  b\[n - 1\] = a\[0\] + a\[1\] + \... + a\[n - 1\] {#bn---1-a0-a1-...-an---1 .unnumbered}

# với n là độ dài của mảng a. {#với-n-là-độ-dài-của-mảng-a. .unnumbered}

# *Ví dụ:* Cho a = \[1, 2, 3\], thì kết quả prefixSums(a) = \[1, 3, 6\]. {#ví-dụ-cho-a-1-2-3-thì-kết-quả-prefixsumsa-1-3-6. .unnumbered}

# Mảng b được tạo ra: \[1, 1 + 2, 1 + 2 + 3\] = \[1, 3, 6\] {#mảng-b-được-tạo-ra-1-1-2-1-2-3-1-3-6 .unnumbered}

# Bài 2: Cho 2 mảng A và B chứa số nguyên. Tìm ra một mảng đã được sắp xếp chứa các phần tử xuất hiện trong mảng B nhưng lại không xuất hiện A {#bài-2-cho-2-mảng-a-và-b-chứa-số-nguyên.-tìm-ra-một-mảng-đã-được-sắp-xếp-chứa-các-phần-tử-xuất-hiện-trong-mảng-b-nhưng-lại-không-xuất-hiện-a .unnumbered}

# Chú ý các phần tử giống nhau chỉ tính là 1 lần xuất hiện {#chú-ý-các-phần-tử-giống-nhau-chỉ-tính-là-1-lần-xuất-hiện .unnumbered}

# Ví dụ: A=\[7,2,5,3,5,3\] và B=\[7,2,5,4,6,3,5,3\] thì kết quả missingValue(A, B) = \[4, 6\] {#ví-dụ-a725353-và-b72546353-thì-kết-quả-missingvaluea-b-4-6 .unnumbered}

# Bài 3: Cho một danh sách các phân số, hãy tìm chỉ số của phân số lớn nhất (đếm từ 0) {#bài-3-cho-một-danh-sách-các-phân-số-hãy-tìm-chỉ-số-của-phân-số-lớn-nhất-đếm-từ-0 .unnumbered}

# Giả định rằng không có các phân số bằng nhau trong tập đầu vào {#giả-định-rằng-không-có-các-phân-số-bằng-nhau-trong-tập-đầu-vào .unnumbered}

# Ví dụ: numerators = \[5, 2, 5\] và denominators = \[6, 3, 4\], thì kết quả maxFraction(numerators, denominators) = 2.  {#ví-dụ-numerators-5-2-5-và-denominators-6-3-4-thì-kết-quả-maxfractionnumerators-denominators-2. .unnumbered}

# 5/4 là phân số lớn nhất, có chỉ số là 2.

# Bài 4: Giả sử menu của chúng ta có các loại thức uống như sau: {#bài-4-giả-sử-menu-của-chúng-ta-có-các-loại-thức-uống-như-sau .unnumbered}

# Cafe {#cafe .unnumbered}

# Cam vắt {#cam-vắt .unnumbered}

# Nước ép cà rốt {#nước-ép-cà-rốt .unnumbered}

# Nước ép cà chua {#nước-ép-cà-chua .unnumbered}

# Nước lọc {#nước-lọc .unnumbered}

# Nước dừa {#nước-dừa .unnumbered}

# Viết một chương trình gọi thức uống đơn giản. {#viết-một-chương-trình-gọi-thức-uống-đơn-giản. .unnumbered}

# Gợi ý: Trước tiên in ra màn hinh danh sách các loại thức uống cho người dùng chọn lựa {#gợi-ý-trước-tiên-in-ra-màn-hinh-danh-sách-các-loại-thức-uống-cho-người-dùng-chọn-lựa .unnumbered}

# Đánh dấu theo thứ tự 1 (cafe), 2 (cam vắt), 3(nước ép cà rốt), 4(nước ép cà chua), 5(nước lọc), 6(nước dừa), 7(thoát gọi món) {#đánh-dấu-theo-thứ-tự-1-cafe-2-cam-vắt-3nước-ép-cà-rốt-4nước-ép-cà-chua-5nước-lọc-6nước-dừa-7thoát-gọi-món .unnumbered}

# Khi người dùng lựa chọn 1 trong số các thức uống, chương trình sẽ hiện đơn giá của thức uống đó và cho phép người dùng nhập số lượng. Cuối cùng hiển thị tổng số tiền người dùng cần phải trả. {#khi-người-dùng-lựa-chọn-1-trong-số-các-thức-uống-chương-trình-sẽ-hiện-đơn-giá-của-thức-uống-đó-và-cho-phép-người-dùng-nhập-số-lượng.-cuối-cùng-hiển-thị-tổng-số-tiền-người-dùng-cần-phải-trả. .unnumbered}

# Sử dụng vòng lặp do while lặp lại cho người dùng đặt thức uống, kết thúc quá trình đặt thức uống khi người nhấn số 7 {#sử-dụng-vòng-lặp-do-while-lặp-lại-cho-người-dùng-đặt-thức-uống-kết-thúc-quá-trình-đặt-thức-uống-khi-người-nhấn-số-7 .unnumbered}

# Yêu cầu 4 (String)

# Bài 1: Viết một hàm chuẩn hóa xâu ký tự: biến đổi xâu ký tự thành xâu sao cho trong xâu không có 2 dấu cách liền nhau và bắt đầu mỗi từ phải in hoa. Ví dụ tRuong TaN HAI =\> Truong Tan Hai. {#bài-1-viết-một-hàm-chuẩn-hóa-xâu-ký-tự-biến-đổi-xâu-ký-tự-thành-xâu-sao-cho-trong-xâu-không-có-2-dấu-cách-liền-nhau-và-bắt-đầu-mỗi-từ-phải-in-hoa.-ví-dụ-truong-tan-hai-truong-tan-hai. .unnumbered}

# Và một hàm tìm từ dài nhất trong 1 xâu ký tự. Hàm main sử dụng các hàm này để nhập xâu ký tự từ bàn phím, in ra xâu trước và sau khi chuẩn hóa, 1 từ dài nhất trong xâu đó. {#và-một-hàm-tìm-từ-dài-nhất-trong-1-xâu-ký-tự.-hàm-main-sử-dụng-các-hàm-này-để-nhập-xâu-ký-tự-từ-bàn-phím-in-ra-xâu-trước-và-sau-khi-chuẩn-hóa-1-từ-dài-nhất-trong-xâu-đó. .unnumbered}

# Bài 2: Cho xâu kí tự. Hãy đếm số lượng kí tự khác nhau trong xâu đó {#bài-2-cho-xâu-kí-tự.-hãy-đếm-số-lượng-kí-tự-khác-nhau-trong-xâu-đó .unnumbered}

# Ví dụ: s = \"cabca\", thì kết quả differentSymbolsNaive(s) = 3. {#ví-dụ-s-cabca-thì-kết-quả-differentsymbolsnaives-3. .unnumbered}

# Có 3 kí tự khác nhau là a, b và c.

# Bài 3: Cho hai xâu kí tự, tìm số lượng kí tự chung giữa chúng. {#bài-3-cho-hai-xâu-kí-tự-tìm-số-lượng-kí-tự-chung-giữa-chúng. .unnumbered}

# Ví dụ: s1 = \"aabcc\" và s2 = \"adcaa\", thì kết quả commonCharacterCount(s1, s2) = 3. {#ví-dụ-s1-aabcc-và-s2-adcaa-thì-kết-quả-commoncharactercounts1-s2-3. .unnumbered}

# 2 xâu s1 và s2 có 3 kí tự chung: 2 kí tự \'a\' và 1 kí tự \'c\'.

# Yêu cầu 5 (Mảng 2 chiều)

# Bài 1: Viết hàm tính tổng các số chẵn trong ma trận có kích thước m\*n. Với m, n là các số nhập từ bàn phím. {#bài-1-viết-hàm-tính-tổng-các-số-chẵn-trong-ma-trận-có-kích-thước-mn.-với-m-n-là-các-số-nhập-từ-bàn-phím. .unnumbered}

# Bài 2: Viết hàm liệt kê các số nguyên tố trong mảng 2 chiều, đếm các số nguyên tố có trong mảng đó. {#bài-2-viết-hàm-liệt-kê-các-số-nguyên-tố-trong-mảng-2-chiều-đếm-các-số-nguyên-tố-có-trong-mảng-đó. .unnumbered}

# Bài 3: Viết hàm tìm giá trị lớn nhất, nhỏ nhất trong mảng 2 chiều {#bài-3-viết-hàm-tìm-giá-trị-lớn-nhất-nhỏ-nhất-trong-mảng-2-chiều .unnumbered}

# Yêu cầu 6 (OOP)

# Xây dựng hệ thống quản lý học viên CODEGYM {#xây-dựng-hệ-thống-quản-lý-học-viên-codegym .unnumbered}

# Đối với mỗi học viên sẽ có các thông tin: {#đối-với-mỗi-học-viên-sẽ-có-các-thông-tin .unnumbered}

# Mã học viên

# Tên

# Lớp

# Email

# Ngày sinh

# Module

# Xây dựng hệ thống quản lý học viên và kết quả sau kỳ thi với các yêu cầu như sau: {#xây-dựng-hệ-thống-quản-lý-học-viên-và-kết-quả-sau-kỳ-thi-với-các-yêu-cầu-như-sau .unnumbered}

# 1. Hiển thị tất cả học viên có trong danh sách. {#hiển-thị-tất-cả-học-viên-có-trong-danh-sách. .unnumbered}

# 2. Thêm mới học viên {#thêm-mới-học-viên .unnumbered}

# 3. Sửa thông tin học viên {#sửa-thông-tin-học-viên .unnumbered}

# 4. Xóa học viên. {#xóa-học-viên. .unnumbered}

# Chi tiết các yêu cầu: {#chi-tiết-các-yêu-cầu .unnumbered}

# 1. Đối với chức năng hiển thị học viên có trong danh sách sẽ được hiển thị dưới dạng bảng trên màn hình với giao diện tương tự dưới đây {#đối-với-chức-năng-hiển-thị-học-viên-có-trong-danh-sách-sẽ-được-hiển-thị-dưới-dạng-bảng-trên-màn-hình-với-giao-diện-tương-tự-dưới-đây .unnumbered}

# ![](media/image1.png){width="6.5in" height="2.296527777777778in"} {#section-17 .unnumbered}

# 2. Khi click vào button thêm mới học viên chương trình sẽ hiển thị hộp thoại prompt() cho người dùng nhập thông tin của học viên. Sau khi người dùng nhập đầy đủ thông tin thì học viên sẽ được thêm vào danh sách. {#khi-click-vào-button-thêm-mới-học-viên-chương-trình-sẽ-hiển-thị-hộp-thoại-prompt-cho-người-dùng-nhập-thông-tin-của-học-viên.-sau-khi-người-dùng-nhập-đầy-đủ-thông-tin-thì-học-viên-sẽ-được-thêm-vào-danh-sách. .unnumbered}

# 3. Khi người dùng click vào button sửa thông tin học viên, chương trình sẽ hiển thị hộp thoại prompt() cho người dùng nhập vào mã học viên cần sửa chữa.  {#khi-người-dùng-click-vào-button-sửa-thông-tin-học-viên-chương-trình-sẽ-hiển-thị-hộp-thoại-prompt-cho-người-dùng-nhập-vào-mã-học-viên-cần-sửa-chữa. .unnumbered}

# Nếu mã học viên tồn tại thì sẽ cho người dùng sửa thông tin của học viên đó. Sau khi sửa xong thông tin được thay đổi lại trên màn hình danh sách. {#nếu-mã-học-viên-tồn-tại-thì-sẽ-cho-người-dùng-sửa-thông-tin-của-học-viên-đó.-sau-khi-sửa-xong-thông-tin-được-thay-đổi-lại-trên-màn-hình-danh-sách. .unnumbered}

# Còn nếu mã không tồn tại thì sẽ hiển thị hộp thoại thông báo cho người dùng " Mã học viên không tồn tại". {#còn-nếu-mã-không-tồn-tại-thì-sẽ-hiển-thị-hộp-thoại-thông-báo-cho-người-dùng-mã-học-viên-không-tồn-tại. .unnumbered}

# 4. Khi người dùng click vào button xóa thông tin, chương trình sẽ hiển thị hộp thoại prompt() cho người dùng nhập vào mã học viên cần sửa chữa {#khi-người-dùng-click-vào-button-xóa-thông-tin-chương-trình-sẽ-hiển-thị-hộp-thoại-prompt-cho-người-dùng-nhập-vào-mã-học-viên-cần-sửa-chữa .unnumbered}

# Nếu mã học viên tồn tại thì sẽ cho người dùng chọn xóa hoặc không. Nếu người dùng chọn xóa thì học viên sẽ mất đi trên màn hình danh sách còn nếu chọn không thì giữ sẽ giữ lại danh sách cũ. {#nếu-mã-học-viên-tồn-tại-thì-sẽ-cho-người-dùng-chọn-xóa-hoặc-không.-nếu-người-dùng-chọn-xóa-thì-học-viên-sẽ-mất-đi-trên-màn-hình-danh-sách-còn-nếu-chọn-không-thì-giữ-sẽ-giữ-lại-danh-sách-cũ. .unnumbered}

# Ngoài ra nếu mã không tồn tại thì sẽ hiển thị hộp thoại thông báo cho người dùng " Mã học viên không tồn tại". {#ngoài-ra-nếu-mã-không-tồn-tại-thì-sẽ-hiển-thị-hộp-thoại-thông-báo-cho-người-dùng-mã-học-viên-không-tồn-tại. .unnumbered}

#  Yêu cầu nâng cao: {#yêu-cầu-nâng-cao .unnumbered}

#  Đối với chức năng thêm mới: {#đối-với-chức-năng-thêm-mới .unnumbered}

# Mã học viên là duy nhất không trùng lặp và có định dạng HV-XXXX ( với XXXX là 4 chữ số )

# Tên học viên chỉ được tối đa 50 ký tự.

# Module chỉ được nhập từ 1 -\> 6

# Ngày sinh đúng định dạng dd/mm/yyyy ( ngày / tháng / năm )

#  {#section-18 .unnumbered}

# Yêu cầu 7.

# Xây dựng giao diện như hình bên dưới: {#xây-dựng-giao-diện-như-hình-bên-dưới .unnumbered}

# ![](media/image2.png){width="6.514488188976378in" height="2.960932852143482in"} {#section-19 .unnumbered}

#  {#section-20 .unnumbered}
