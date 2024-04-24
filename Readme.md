# OverTheWireLabs
OverTheWireLabs

# Level 0 
![253224368-8db0502f-7e0c-4055-a754-7b15db9a8598](https://github.com/trishuy/OverTheWireLabs/assets/95763623/5740b66f-0f46-4163-9a0e-da34bcc4e3ad)

Chuyển hướng vào webpage và sử dụng tài khoản và mật khẩu đã được cung cấp 

username:```natas0```          password:```natas0```

![Screenshot 2024-04-22 154018](https://github.com/trishuy/OverTheWireLabs/assets/95763623/568505ad-b5fa-4212-a6d6-ee4a074cd8ce)

Kiểm tra nguồn trang và ta có được mật khẩu 

![Screenshot 2024-04-22 154412](https://github.com/trishuy/OverTheWireLabs/assets/95763623/86920ea2-6adf-4f17-8881-f9e5e114fbc4)

# Level 1
![Screenshot 2024-04-22 154914](https://github.com/trishuy/OverTheWireLabs/assets/95763623/c270a5f2-5850-43ea-9d50-99abdc77b60a)

tiếp tục chuyển hướng đến web lab với tài khoản đã được cho và mật khẩu được tìm thấy ở Level 0

username:```natas1```          password:```g9D9cREhslqBKtcA2uocGHPfMZVzeFK6```

![Screenshot 2024-04-22 155208](https://github.com/trishuy/OverTheWireLabs/assets/95763623/caf52944-c53e-4e96-938b-c8b9f14cbccb)

Vì Right-clicking bị block nên chúng ta có thể sử dụng tổ hợp ```ctrl + u``` để xem nguồn trang 

![Screenshot 2024-04-22 155447](https://github.com/trishuy/OverTheWireLabs/assets/95763623/8c3fcd1f-cd55-4883-acbc-b8dbbedae0c1)

Và chúng ta đã tìm ra mật khẩu cho bài lab tiếp theo

# Level 2
![Screenshot 2024-04-22 160114](https://github.com/trishuy/OverTheWireLabs/assets/95763623/ff661f71-9bca-48a5-9338-6309f8230cc7)

tiếp tục chuyển hướng đến web lab với tài khoản đã được cho và mật khẩu được tìm thấy ở Level 1

username:```natas2```          password:```h4ubbcXrWqsTo7GGnnUMLppXbOogfBZ7```

![Screenshot 2024-04-22 160847](https://github.com/trishuy/OverTheWireLabs/assets/95763623/5b14a627-a32b-4f8e-864a-9d4f92f9a94a)

check nguồn trang và ta thấy được ```<img src="files/pixel.png">. ```

![Screenshot 2024-04-22 162739](https://github.com/trishuy/OverTheWireLabs/assets/95763623/351a9df1-4c11-4125-911d-a9f2d5885c61)

Đây là hình ảnh png, điều này có nghĩa là hình ảnh nằm trong url ```http://natas2.natas.labs.overthewire.org/files/pixel.png```, nếu chúng ta quay lại một thư mục thì chúng ta sẽ có ```http://natas2.natas.labs.overthewire.org/files```. Điều hướng đến trang web ,ta sẽ thấy được 

![image](https://github.com/trishuy/OverTheWireLabs/assets/95763623/ca78dc3c-3d4d-45e5-9dbb-e151cc1119ed)

Truy cập vào ```users.txt``` và ta có được mật khẩu 

![image](https://github.com/trishuy/OverTheWireLabs/assets/95763623/66f28f80-96f9-4568-bb60-9e7f657bf120)

# Level 3
![253234387-0c6847f0-a5db-46a3-95df-40ccd09a327e](https://github.com/trishuy/OverTheWireLabs/assets/95763623/314e5164-cb67-405e-9601-b2ece2acda3b)

tiếp tục chuyển hướng đến web lab với tài khoản đã được cho và mật khẩu được tìm thấy ở Level 2

username:```natas3```          password:```G6ctbMJ5Nb4cbFwhpMPSvxGHhQ7I6W8Q```

![image](https://github.com/trishuy/OverTheWireLabs/assets/95763623/923eb65a-01d4-44f0-821f-40da6f4b0003)

tiếp tục vào xem nguồn trang

![image](https://github.com/trishuy/OverTheWireLabs/assets/95763623/8d5af6ee-c967-40f4-bc40-fe61778134aa)

như chúng ta có thể thấy được rằng sẽ không có thể tin nào leaks ra và kể cả search google cũng không có

![Screenshot 2024-04-24 094818](https://github.com/trishuy/OverTheWireLabs/assets/95763623/a21b5655-ec7d-44d2-8e8c-057d545b5588)

thế nên dựa vào instruct web chúng ta có thể biết rằng trong web này sẽ có robots.txt ( các bạn có thể truy cập web https://www.robotstxt.org/robotstxt.html để tìm hiểu thêm )

điều hướng đến ```http://natas3.natas.labs.overthewire.org/robots.txt``` nó cho ra thư mực không cho phép tên là  ```/s3cr3t/``` 
![image](https://github.com/trishuy/OverTheWireLabs/assets/95763623/6749b677-7690-4521-8a47-6b8813478417)

tiếp tục điều hướng đến thư mục ```/s3cr3t/``` nó cho  file đó chính là ```user.txt```

![image](https://github.com/trishuy/OverTheWireLabs/assets/95763623/e3132740-9cc7-4a98-8ccd-c52d54edb998)

truy cập và ta biết được mật khẩu được bài lab tiếp theo .

![image](https://github.com/trishuy/OverTheWireLabs/assets/95763623/d3ecf106-b1f9-4ed9-bb8b-89445a4905d0)

# Level 4
![image](https://github.com/trishuy/OverTheWireLabs/assets/95763623/c49559e2-1f15-4522-a3d9-64d9db087621)

tiếp tục chuyển hướng đến web lab với tài khoản đã được cho và mật khẩu được tìm thấy ở Level 2

username:```natas4```          password:```tKOcJIbzM4lTs8hbCmzn5Zr4434fGZQm```

Để có thể truy cập được trang web thành công, chúng ta cần phải đảm bảo rằng truy cập đến url được chỉ định 

=> Để làm được điều này , chúng ta cần phải request đến địa chỉ đúng của url

![image](https://github.com/trishuy/OverTheWireLabs/assets/95763623/5940e9da-92fc-40dc-bf77-210a1e36e486)

![image](https://github.com/trishuy/OverTheWireLabs/assets/95763623/7fdfd313-479e-4fca-8750-09aebf218d07)



















