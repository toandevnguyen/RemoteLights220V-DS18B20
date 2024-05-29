# Ứng Dụng Android Điều Khiển Đèn IoT Và Hiển Thị Nhiệt Độ

## Tổng Quan Dự Án
- Repository này chứa mã nguồn cho ứng dụng Android tương tác với hệ thống IoT sử dụng vi điều khiển ESP32-C3. Ứng dụng cho phép người dùng điều khiển đèn 220V từ xa và giám sát nhiệt độ bằng cảm biến DS18B20 thông qua MQTT qua TCP.
- [Liên Kết Video Demo](https://24ffdk-my.sharepoint.com/:v:/g/personal/toan5tb1drivedev_24ffdk_onmicrosoft_com/EdekrNNiyAdAr4RuuM1K9csBAXf8sxO2ubKTF2UoG07UlA?e=lwrZPB) 

## Tính Năng
- Điều khiển đèn 220V từ xa qua MQTT
- Hiển thị nhiệt độ thực tế từ cảm biến DS18B20
- Giao diện thân thiện với người dùng

## Công Nghệ Sử Dụng
- **Phần Cứng**:
  - ESP32-C3
    ![ESP32-C3](https://i.ebayimg.com/images/g/WkEAAOSw1iZli80j/s-l500.jpg)
  - Cảm Biến Nhiệt Độ DS18B20
    ![DS18B20](https://i.ebayimg.com/images/g/6sYAAOSwnmxfhlJE/s-l1600.webp)
  - Module Rơ-le 5V 1 kênh
    ![Relay](https://bizweb.dktcdn.net/100/005/602/files/ad4.jpg?v=1465956650836)
  - Bóng Đèn Led
    ![Led Bulb](https://kawaled.com/image/catalog/bulb-tru---tron-led2/den-led-tron-led2-a60-9w.jpg)
- **Phần Mềm**: Android (Java/Kotlin), ESP-IDF Visual Studio Code Extension, MQTT Explorer, Giao tiếp TCP

## Hướng Dẫn Cài Đặt
1. **Cài Đặt Backend**:
   - Làm theo hướng dẫn trong repository [IoT-ESP32-C3-MQTT-TCP-RemoteLed-DS18B20](https://github.com/yourusername/IoT-ESP32-C3-MQTT-TCP-RemoteLed-DS18B20) để thiết lập phần cứng và phần mềm.

2. **Cài Đặt Ứng Dụng Di Động**:
   - Clone repository: `git clone https://github.com/yourusername/Android-App-IoT-ESP32C3-MQTT-TCP-RemoteLights220V-DS18B20`
   - Mở dự án trong Android Studio.
   - Cấu hình cài đặt MQTT broker trong mã nguồn của ứng dụng.
   - Build và chạy ứng dụng trên thiết bị Android.

## Sử Dụng
- Sử dụng ứng dụng để kết nối với hệ thống IoT.
- Điều khiển đèn 220V và xem dữ liệu nhiệt độ theo thời gian thực.

## Đóng Góp
Hoan nghênh đóng góp! Vui lòng xem [CONTRIBUTING.md](CONTRIBUTING.md) để biết hướng dẫn.

## Giấy Phép
Dự án này được cấp phép theo giấy phép MIT - xem file [LICENSE](LICENSE) để biết chi tiết.

## Ngôn Ngữ
- [English](../README.md)