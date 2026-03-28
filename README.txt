DSV Shipping Mark Label Generator - Final Fixed

สิ่งที่แก้ไขในเวอร์ชันนี้
- ไม่จำข้อมูลเก่าแล้ว (ลบ localStorage restore/save ออก)
- ลบปุ่ม Save in Browser ออก
- เปิดหน้าเว็บมาแล้วไม่โหลด sample data อัตโนมัติ
- ตอนกด Print จะตั้งชื่อเอกสารเป็น "Shipping mark T." ชั่วคราว เพื่อให้ browser ใช้เป็นชื่อไฟล์ตั้งต้นเวลา Save as PDF

หมายเหตุ
- ชื่อไฟล์สุดท้ายในหน้าต่าง Save/Print ยังขึ้นอยู่กับ browser และเครื่องพิมพ์/PDF printer ของผู้ใช้
- โดยทั่วไป browser มักใช้ document title เป็นชื่อเริ่มต้น ทำให้ผู้ใช้เติมส่วนท้ายเองต่อได้


Deploy-ready สำหรับ GitHub Pages
- ใช้ index.html เป็น entry file สำหรับ GitHub Pages
- ใช้ DSV_Shipping_Mark_Label_Generator_Final_Fixed.html เป็นไฟล์ชื่อทางการสำรอง
- เวอร์ชันนี้ไม่จำข้อมูลเก่า, ไม่มี Save in Browser, และตั้งชื่อเอกสารตอน Print เป็น Shipping mark T.
