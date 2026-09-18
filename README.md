# GOLD Trading Journal

บันทึกการเทรดทอง/forex รายไม้ แล้วอ่านย้อนเป็นภาพรวมตอนสิ้นเดือน

- หน้าเดียว ไม่มี build step — เปิด `index.html` ได้เลย
- เก็บใน localStorage + sync ขึ้น Firestore ด้วยบัญชี Google (เปิดที่เครื่องไหนก็เห็นข้อมูลเดียวกัน)
- บันทึก: ทิศทาง, lot, เข้า/SL/TP/ออก, R:R (คำนวณให้), ช่วงตลาด, timeframe, อารมณ์, เหตุผล, รีวิวหลังจบไม้, รูปกราฟ
- กรอกเงินเป็น USD แสดงบาทคู่กัน (ตั้งเรทในแท็บแผนพอร์ต)
- Dashboard: win rate, P&L, equity curve, และสถิติแยกตามช่วงตลาด / Buy-Sell / timeframe

## เทสต์

```
npm i
npm test          # ตรรกะ merge/sync (ไม่ต้องใช้เบราว์เซอร์)
npm run test:browser   # โหลดหน้าจริงใน headless Chrome
```
