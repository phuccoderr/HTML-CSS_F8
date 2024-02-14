# Nhúng CSS vào HTML
- External CSS: viết CSS ở một file riêng, đặt tên là <name>.css, sau đó sử dụng thẻ link để nhúng file này vào trong phần <head> của file html.
- Internal CSS: đặt trong mục head của file html, được cấu trúc bằng cặp thẻ <style></style>
- Inline CSS: áp dụng trực tiếp vào phần tử. CSS bằng cách này không được khuyến khích, việc quản lý file sẽ rất khó nếu chỉ sử dụng Inline CSS, vì nó chỉ áp dụng cho một element duy nhất
# Đơn vị CSS
- %: phần trăm, là đơn vị tham chiếu tỉ lệ so với một phần tử mẹ dựa vào kích thước.
- in: inch (1 inch = 2,54 cm).
- em: 1em tương đương với kích thước font chữ hiện hành, nếu font hiện hành có kích thước 14px thì 1em = 14px.
- ex: 1ex bằng chiều cao của chữ x hiện hành.
- pt: Point (1pt = 1/72 inch).
- pc: Pica (1pc = 12pt).
- px: Pixel (điểm ảnh trên màn hình máy tính).
- cm: định nghĩa đơn vị đo bằng cm.
- mm: định nghĩa đơn vị đo bằng mm.
- vh: 1% chiều cao của khung nhìn.
- vw: 1% chiều rộng của khung nhìn.
# Sự ưu tiên về vị trí đặt CSS
CSS Nội tuyến > CSS bên trong > CSS bên ngoài > CSS mặc định của trình duyệt
# Background
- background-color
- background-image
- background-repea
  + repeat-x: Lặp lại theo phương ngang
  + repeat-y: Lặp lại theo phương dọc
  + repeat: Lặp lại theo 2 phương (Đây là giá trị mặc định) 
  + no-repeat: Không lặp lại ảnh
- background-attachment ( Khóa ảnh nền )
  + scroll: Ảnh nền cuộn xuống cùng nội dung trang web (Giá trị mặc định)
  + fixed: Ảnh nền cố định khi cuộn nội dung trang web.
- background-position
  + background-position: 5cm 2cm ( example )
# Box Model 
- Margin: Khoảng cách tính từ bên ngoài của phần tử
- Padding: Khoảng cách tính từ bên trong của phần tử
- Content: Nội dung trong phần tử
- border-radius: bo tròn
- Border: Đường viền của phần tử
  + none: Không có đường viền
  + hidden: Đường viền bị ẩn đi
  + solid: Đường viền kiểu nét liền thông thường
  + dashed: Đường viền kiểu nét đứt
  + dotted: Đường viền kiểu chấm chấm
  + double: Đường viền kép
  + groove: Đường viền kiểu đường rãnh
  + ridge: Đường viền kiểu lồi lên
  + inset: Đường viền kiểu inset
  + outset: Đường viền kiểu outset
  + initial: Sử dụng giá trị mặc định của nó. Thông thường sẽ là none
  + inherit: Kế thừa giá trị của phần tử html cha
# Font Chữ 
- Font-family ( kiểu chữ )
  + family-names: Tên cụ thể của font: Roboto, Arial, Time New Roman…
  + generic families: Tên của một họ gồm nhiều font: sans-serif, serif,…
- Font-style (  in thường, in nghiêng, hay in xiên cho chữ... )
  + font-style: italic ( example )
- Font-weight ( chế độ bình thường hay in đậm )
  + font-weight: bold ( example )
- Font-size ( kích thước chữ )
# Text
- Text-indent ( thụt đầu dòng ).
- Text-align ( left (canh trái), right (canh phải), center (canh giữa), justify (canh đều) ).
- Letter-spacing ( hỉnh khoảng cách giữa các ký tự trong một văn bản ).
- Text-decoration
  + underline (gạch chân)
  + line-through (gạch xiên)
  + overline (gạch đầu)
  + blink (hiệu ứng nhấp nháy)
- Text-transform
	+ uppercase (in hoa)
 	+ lowercase (in thường)
  + capitalize (in hoa ký tự đầu tiên trong mỗi từ)
  + none (không áp dụng hiệu ứng) ).

    
