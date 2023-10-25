# Demo MOMO Payment

Dự án demo về thanh toán bằng MOMO sử dụng tài khoản thử nghiệm.

## Yêu cầu để chạy

Để chạy dự án này, bạn cần thực hiện các bước sau:

1. **Tải và cài đặt MOMO APP FOR DEVELOPER**: 
   Truy cập [MOMO APP FOR DEVELOPER](https://developers.momo.vn/v3/download/) để tải ứng dụng MOMO.
   Cài đặt ứng dụng trên thiết bị của bạn. 
   Nếu bạn đang sử dụng máy ảo, hãy chạy ứng dụng máy ảo và kéo và thả file cài đặt vào máy ảo để bắt đầu quá trình cài đặt.
   Sau khi cài đặt xong, mở ứng dụng MOMO và thực hiện đăng ký tài khoản, liên kết ngân hàng và nạp tiền theo hướng dẫn tại [đây](https://developers.momo.vn/v3/vi/docs/payment/onboarding/test-instructions/).

2. **Import SDK vào dự án**: 
   Truy cập [GitHub repository của MOMO SDK](https://github.com/momo-wallet/mobile-sdk) để import SDK vào dự án của bạn.
   
   ***Ở đây tôi import theo android studio của tôi nên có thể hơi khác so với link từ MOMO SDK***
   
   ***ở file build.gradle.kts(Module:app)***
   ![import1](https://github.com/nvtiendev/Payment/blob/main/import1.png)
   ***ở file settings.gradle.kts***
   ![import2](https://github.com/nvtiendev/Payment/blob/main/import2.png)
   
##Bắt đầu
   
   ***Và sau khi đã cài đặt xong thì hãy tạo 1 button ở layout như hình đó***
   ![Layout](https://github.com/nvtiendev/Payment/blob/main/button.png)
   
   ***tiếp đó ta sẽ cài đặt MainActivity***
   ![MainActivity](https://github.com/nvtiendev/Payment/blob/main/MainActivity.png)
   
   ![MainActivity2](https://github.com/nvtiendev/Payment/blob/main/MainActivity2.png)
   
   ![MainActivity3](https://github.com/nvtiendev/Payment/blob/main/MainActivity3.png)

***và sau đó hãy chạy thử để test***