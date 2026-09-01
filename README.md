# AD Library — Web App แบบไม่ต้องติดตั้ง

เปิดผ่าน Safari บน iPhone/iPad หรือเบราว์เซอร์มือถืออื่นได้ทันที

## วิธีใช้งาน
1. อัปโหลดไฟล์ `index.html` ไปยัง GitHub Pages หรือพื้นที่เว็บของมหาวิทยาลัย
2. เปิด URL ผ่าน Safari / Chrome / Edge
3. ไม่ต้องติดตั้งแอพ

## ฟังก์ชัน
- Dashboard
- เพิ่มหนังสือ
- เพิ่มสมาชิก
- ยืม / คืน
- ตรวจรายการเกินกำหนด
- ค้นหาหนังสือ
- Print
- Import Excel
- Export Excel
- Backup JSON
- Responsive สำหรับ iPhone / iPad / Android / Desktop

## สำคัญ
รุ่นนี้เก็บข้อมูลด้วย LocalStorage ในเบราว์เซอร์ของอุปกรณ์แต่ละเครื่อง
ดังนั้นข้อมูลจะไม่แชร์ข้ามอุปกรณ์อัตโนมัติ

หากต้องการให้ iPhone, iPad และคอมพิวเตอร์หลายเครื่องใช้ฐานข้อมูลเดียวกัน
ต้องเพิ่ม Cloud Database / Backend เช่น Firebase, Supabase หรือ Server ของมหาวิทยาลัย

## Excel
ไฟล์ Excel ใช้ชีต:
- Books
- Members
- Loans

การ Import/Export Excel ใช้ SheetJS จาก CDN จึงต้องเชื่อมต่ออินเทอร์เน็ตในเวลาที่ใช้งานฟังก์ชัน Excel
