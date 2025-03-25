**Phần I:**
Sử dụng github action để:

1. Build docker image rồi publish lên docker hub:

![Screenshot 2025-03-25 153453](https://github.com/user-attachments/assets/fe0ecb89-fe29-423d-9ff3-0482d76ee873)

2. docker images cho frontend va backend đã được tạo và up lên docker hub

![Screenshot 2025-03-25 153515](https://github.com/user-attachments/assets/4df35f94-6be1-4e30-860e-d3e1bd813d02)

3. Sử dụng agroCD để pull k8s manifest, dockerimage và chạy trên local k8s cluster:

![Screenshot 2025-03-25 162131](https://github.com/user-attachments/assets/8875e2d8-a8ad-47cf-8dc4-08f915ece9c0)

4. Khi pull cluster thành công và chạy các pod trên local cluster:

![image](https://github.com/user-attachments/assets/02f26e6d-dcb6-4761-ba0d-5b980c86745b)

5. Khi này đã có thể truy cập cổng 8080 của frontend trên browser thông qua k8s pod

![Screenshot 2025-03-18 141453](https://github.com/user-attachments/assets/089c4be2-4df3-4ac1-8ba1-d681a1b1e008)

