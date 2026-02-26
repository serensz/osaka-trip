# 🗾 Osaka Trip Plan — GitHub Pages

แผนเที่ยวโอซาก้า 27 Feb – 2 Mar พร้อมข้อมูลการเดินทางทุกจุด  
ดูได้บนมือถือ/ทุกหน้าจอ

---

## 🚀 วิธี Host บน GitHub Pages (ทำครั้งเดียว ~5 นาที)

### ขั้นตอนที่ 1 — สร้าง Repository ใหม่

1. เปิด [github.com](https://github.com) → กด **"+"** มุมบนขวา → **New repository**
2. ตั้งชื่อ repo เช่น `osaka-trip` (หรืออะไรก็ได้)
3. เลือก **Public** (ถ้า Private ต้องเป็น GitHub Pro)
4. **ไม่ต้องติ๊ก** Add README / .gitignore
5. กด **Create repository**

---

### ขั้นตอนที่ 2 — Upload ไฟล์

**วิธี A — ผ่าน Browser (ง่ายที่สุด)**

1. ใน repo ที่เพิ่งสร้าง กด **"uploading an existing file"**
2. ลาก `index.html` ใส่
3. เขียน commit message เช่น `Add trip plan`
4. กด **Commit changes**

**วิธี B — ผ่าน Terminal (ถ้ามี Git)**

```bash
cd osaka-trip
git init
git add index.html
git commit -m "Add Osaka trip plan"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/osaka-trip.git
git push -u origin main
```

---

### ขั้นตอนที่ 3 — เปิด GitHub Pages

1. ไปที่ repo → คลิกแท็บ **Settings**
2. เมนูซ้าย คลิก **Pages**
3. ใต้ **Branch** เลือก `main` → folder `/root`
4. กด **Save**
5. รอ ~1-2 นาที แล้ว refresh

✅ URL จะขึ้นมา:  
**`https://YOUR_USERNAME.github.io/osaka-trip/`**

---

### ขั้นตอนที่ 4 — บันทึก URL บนมือถือ

- เปิด URL บน Safari/Chrome → กด **Share → Add to Home Screen**
- จะได้ไอคอนบน home screen ใช้งานได้เหมือน app!

---

## 📁 ไฟล์

```
osaka-trip/
└── index.html   ← ไฟล์เดียว ทุกอย่างอยู่ในนี้
```

---

## ✏️ แก้ไขเนื้อหา

แก้ได้โดยตรงใน `index.html`  
หรือแก้บน GitHub ผ่าน browser: เปิดไฟล์ → กดไอคอนดินสอ ✏️ → แก้ → Commit

---

*Safe travels! ✈️*
