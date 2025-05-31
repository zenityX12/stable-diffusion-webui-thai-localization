# ไฟล์แปลภาษาไทยสำหรับ AUTOMATIC1111 Stable Diffusion WebUI

[![ชีลด์ GitHub](https://img.shields.io/badge/GitHub-Repository-blue.svg)]([https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME](https://github.com/zenityX12/stable-diffusion-webui-thai-localization/))  ชุดไฟล์แปลภาษาไทยสำหรับส่วนติดต่อผู้ใช้ (UI) ของโปรแกรม AUTOMATIC1111 Stable Diffusion WebUI เพื่อให้ผู้ใช้งานชาวไทยสามารถใช้งานโปรแกรมได้ง่ายและเข้าใจมากยิ่งขึ้น

**อัปเดตล่าสุด/แปลจากเวอร์ชัน:** 1.10.1

## คุณสมบัติ

* แปลเมนู, ปุ่ม, คำอธิบาย และส่วนประกอบต่างๆ ของ UI หลักเป็นภาษาไทย
* พยายามคงคำศัพท์เทคนิคและคำทับศัพท์ที่ใช้กันทั่วไปไว้เพื่อความเข้าใจ
* อัปเดตให้ครอบคลุมการตั้งค่าและฟังก์ชันต่างๆ (ณ วันที่ทำการแปล)

## วิธีการติดตั้ง

1.  **ดาวน์โหลดไฟล์ภาษาไทย:**
    * ไปที่หน้า Repository นี้บน GitHub
    * คลิกที่ปุ่มสีเขียว `Code` จากนั้นเลือก `Download ZIP` หรือดาวน์โหลดเฉพาะไฟล์ `th_TH.json` ที่อยู่ในโฟลเดอร์ `localizations` ของ Repository นี้

2.  **แตกไฟล์ (ถ้าดาวน์โหลดแบบ ZIP):**
    * หากคุณดาวน์โหลดเป็นไฟล์ ZIP ให้ทำการแตกไฟล์ออกมา จะได้ไฟล์ `th_TH.json`

3.  **คัดลอกไฟล์ไปยังโฟลเดอร์ของ Stable Diffusion WebUI:**
    * เปิดโฟลเดอร์ที่คุณติดตั้งโปรแกรม AUTOMATIC1111 Stable Diffusion WebUI
    * มองหาโฟลเดอร์ชื่อ `localizations` (หากไม่มี ให้สร้างขึ้นใหม่)
    * นำไฟล์ `th_TH.json` ที่ได้จากขั้นตอนก่อนหน้า ไปวางไว้ในโฟลเดอร์ `localizations` นี้

## วิธีการใช้งาน

1.  เปิดโปรแกรม AUTOMATIC1111 Stable Diffusion WebUI
2.  ไปที่แท็บ **Settings**
3.  ในหน้า Settings มองหาหัวข้อ **Localization** (หรือ User interface / ส่วนติดต่อผู้ใช้)
4.  จากเมนูแบบดรอปดาวน์ ให้เลือก `th_TH` (หรือชื่อไฟล์ภาษาไทยที่คุณใช้)
5.  คลิกปุ่ม **Apply settings** (ใช้การตั้งค่า)
6.  คลิกปุ่ม **Reload UI** (โหลด UI ใหม่) หรือทำการรีสตาร์ทโปรแกรม WebUI เพื่อให้การเปลี่ยนแปลงมีผล

## ความเข้ากันได้

* ไฟล์แปลนี้ได้รับการทดสอบ/สร้างขึ้นจาก Stable Diffusion WebUI เวอร์ชัน 1.10.1
* อาจสามารถใช้ได้กับเวอร์ชันใกล้เคียง แต่บางเมนูหรือข้อความที่เพิ่มเข้ามาใหม่อาจจะยังไม่ได้รับการแปล

## การมีส่วนร่วม (Contributing)

หากคุณพบข้อผิดพลาดในการแปล, คำแปลที่ไม่เหมาะสม, หรือต้องการเสนอคำแปลที่ดีกว่า หรือช่วยแปลส่วนที่ยังขาดหายไป สามารถช่วยกันพัฒนาได้โดย:

* เปิด **Issue** ใน Repository นี้เพื่อแจ้งปัญหาหรือข้อเสนอแนะ
* ทำการ **Fork** Repository นี้, แก้ไขไฟล์ `th_TH.json` แล้วส่ง **Pull Request** กลับมา

ทุกการมีส่วนร่วมยินดีต้อนรับครับ!

## License

"เนื้อหาการแปลนี้เผยแพร่ภายใต้ License เดียวกับโปรเจกต์ AUTOMATIC1111 Stable Diffusion WebUI"

## คำขอบคุณ (Acknowledgements)

* ขอขอบคุณผู้พัฒนา AUTOMATIC1111 Stable Diffusion WebUI สำหรับโปรแกรมที่ยอดเยี่ยม

---

สร้างสรรค์โดย: ZenityX AI Stuido

[![ชีลด์ Page Facebook](https://img.shields.io/badge/Facebook-ติดตามเรา-blue?style=for-the-badge&logo=facebook)]((https://web.facebook.com/zenityXAiStudio/))
