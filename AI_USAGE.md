## 1. Công cụ AI 
Tên công cụ: ChatGPT 
 
## 2. Mục đích sử dụng  
Phân tích giao diện và đề xuất bố cục trang chủ websitet Tiki, hỗ trợ tạo và giải thích mã nguồn HMTL/CSS

## 3. Prompt đã sử dụng 
Prompt 1: Tôi muốn cải tiến khu vực trang chủ của website Tiki, hãy giúp tôi đề xuất bố cục giao diện phù hợp cho trang này

Prompt 2: Dựa trên phương án thiết kế đã thống nhất, hãy tạo một trang giao diện thương mại điện tử bằng HTML5 và CSS3. Giao diện có tiêu đề và khu vực sản phẩm, tối thiểu bốn sản phẩm mẫu; mỗi sản phẩm có hình ảnh, tên, giá và nút thao tác. Bố cục cần phù hợp với màn hình máy tính và điện thoại. Mã HTML có cấu trúc rõ ràng, CSS được tách thành file riêng, không sử dụng backend hoặc cơ sở dữ liệu.

## 4. Kết quả AI đề xuất 
AI đã hỗ trợ đề xuất và triển khai các nội dung chính:
- Bố cục trang chủ gồm header, thanh tìm kiếm, điều hướng, banner, danh mục, khu vực Flash Sale/sản phẩm nổi bật, danh sách sản phẩm, khu vực thương hiệu và footer.
- Sử dụng các phần tử HTML có ý nghĩa như header, nav, main, section, article và footer để tổ chức nội dung.
- Tách phần trình bày CSS khỏi cấu trúc HTML thông qua file css/style.css.
- Sử dụng CSS Grid/Flexbox và media queries để hỗ trợ bố cục trên nhiều kích thước màn hình.
- Tạo các thẻ sản phẩm mẫu với hình ảnh, tên, giá và nút thao tác.
 
## 5. Kiểm tra và điều chỉnh 
Trong quá trình rà soát mã nguồn, phát hiện các liên kết nội bộ trỏ đến mã định danh sản phẩm nhưng thẻ sản phẩm tương ứng chưa có thuộc tính id. Phần HTML được điều chỉnh bằng cách bổ sung id cho các thẻ sản phẩm, bảo đảm giá trị id khớp với giá trị trong thuộc tính href của liên kết.

## 6. Phần tôi hiểu và có thể giải thích 
Các thành phần mã nguồn quan trọng mà tôi hiểu
- header: chứa phần đầu trang như nhận diện website và khu vực tìm kiếm.
- nav: tổ chức các liên kết điều hướng.
- main: chứa nội dung chính của trang chủ.
- section: phân chia nội dung thành từng khu vực như danh mục và sản phẩm nổi bật.
- article: biểu diễn một nội dung sản phẩm độc lập.
- footer: chứa thông tin ở cuối trang.
- class: nhóm các phần tử để áp dụng quy tắc CSS.
- id: định danh duy nhất cho một phần tử, có thể được dùng làm đích của liên kết nội bộ.
- CSS Grid/Flexbox: hỗ trợ sắp xếp các phần tử theo dạng lưới hoặc theo hàng/cột.
- Media query (@media): áp dụng quy tắc CSS khác nhau theo kích thước màn hình.