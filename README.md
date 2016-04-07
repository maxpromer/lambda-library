# LAMBDA Board library for Arduino IDE (Unofficial)
ไลบารี่ที่ใช้ในโปรแกรม Arduino IDE เพื่อใช้งานบอร์ด LAMBDA รุ่น Lift/Basic/Plus ได้เต็มประสิทธิ์ภาพ เนื่องจากบอร์ดนี้ได้ใช้ชิฟตัวใหม่ ATmaga328pb ซึ่งมีความสามารถเพิ่มขึ้นจากรุ่นก่อนๆมาก เช่น มี  UART จำนวน 2 ช่อง จากเดิมที่มีเพียงช่องเดียว

_หมายเหต_* : นี่ไม่ใช่ไลบารี่จากผู้ผลิต จัดทำขึ้นเพื่อใช้งานในระหว่างที่ผู้ผลิตกำลังจัดทำไลบารี่สำหรับบอร์ดโดยเฉพาะ

## การติดตั้ง
* เปิดโปรแกรม Arduino IDE ขึ้นมา จากนั้นกดไปที่ File > Preferences 
* ในช่อง Additional Boards Manager URLs กรอก http://file.host-1gb.com/package_lambda_index.json ลงไป แล้วกดปุ่ม OK
* กดไปที่ Tool > Board > Boards Manager เลื่อนหา LAMBDA Boards กด Install รอจนกว่าจะโหลดเสร็จ จากนั้นปิดหน้าต่างไป
* เลือกบอร์ด เลือกพอร์ต จากนั้นทดลอง Upload ได้เลย

## ลิขสิทธิ์การใช้งาน
ผู้จัดทำอนุญาตให้ใช้งานได้ที่ไม่ใช่ในเชิงพาณีชย์ (เช่น คัดลอกผลงานนี้เพื่อจำหน่าย) ยกเว้นผู้ผลิตบอร์ด LAMBDA และต้องขอบคุณต้นแบบของไฟล์ที่ผู้จัดทำได้นำมาเป็นส่วนประกอบด้วยครับ
* https://github.com/watterott/ATmega328PB-Testing
* http://www.atmel.com/tools/ATMELAVRTOOLCHAINFORWINDOWS.aspx
* http://www.ioxhop.com/
