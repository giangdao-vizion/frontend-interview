# VIZION: Frontend Coding Challenge

Sử dụng React, [@react-three/fiber](https://github.com/pmndrs/react-three-fiber), [@react-three/drei](https://github.com/pmndrs/drei) để tạo ra demo tương tác không gian 360 như sau: [Link demo](https://view.vizion.space/modern-pub/Welcome/Modern-Pub-Entrance-?mode=no-intro)

## Yêu cầu cần đạt được:

- Cần hoàn thành trong vòng 60p, kết quả cần được build và push lên github pages để được đánh giá.
- Hoàn thành Demo không gian cho phép xoay xung quanh để xem toàn cảnh 360 độ. Trong demo cần có các bước chân cho phép nhấn vào để di chuyển tới khung cảnh khác (render hình ảnh khác).
- Hiển thị logo ở 1 góc màn hình.

## Technical Guideline:

- Sử dụng @react-three/fiber > Sphere và các hình ảnh trong "assets/360 images" để tạo ra các khung cảnh. Kết hợp với camera, ánh sáng phù hợp để nhìn thấy rõ ràng các chi tiết.
- Sử dụng @react-three/drei > OrbitControls để tạo tương tác điều khiển xoay.
- @react-three/drei > Html và hình ảnh "assets/footstep.png" để tạo ra các bước chân clickable để chuyển sang khung cảnh (không gian) khác. Các bước chân cần hiển thị nghiêng tương tự như trong demo.
- Hiển thị logo "assets/logo/logo.png" cố định ở góc trên bên phải màn hình. Khi nhấn vào sẽ mở ra website khách hàng (sample.com). Kích thước logo trên mobile: 80x80px, desktop: 150x150px.

## Nộp kết quả:

- Cần hoàn thành trong vòng 60p, kết quả cần được build và push lên github pages để được đánh giá.
- Submit kết quả bằng cách gửi link Github Pages qua địa chỉ email [giang.dao@vizion.space](mailto:giang.dao@vizion.space) và cc các d/c email: [vi.dang@successsoftware.global](mailto:vi.dang@successsoftware.global), [ngoc.nguyen@successsoftware.global](mailto:ngoc.nguyen@successsoftware.global)
