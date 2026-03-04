# 📋 Certificates, Competitions & Activities

เว็บไซต์แสดงผลงาน — รวบรวมใบประกาศนียบัตร การแข่งขัน และกิจกรรมต่าง ๆ ของ Kittiphong Toadonthong พร้อม Lightbox Viewer และระบบ Tab Filter

🔗 **Live Demo:** [kittiphongkubkub.github.io/Certificates-Competitions-Activities](https://kittiphongkubkub.github.io/Certificates-Competitions-Activities)

---

## ✨ ฟีเจอร์หลัก

| ฟีเจอร์ | รายละเอียด |
|--------|-----------|
| 🗂️ Tab Filter | กรองดูตามหมวด (ทั้งหมด / Certificates / Competitions / Activities) |
| 🖼️ Lightbox Viewer | คลิกดูรูปขนาดเต็มพร้อมปุ่มเลื่อนก่อน/หลัง |
| ⌨️ Keyboard Navigation | กด `←` `→` เพื่อเลื่อนรูป, `Esc` เพื่อปิด |
| 📱 Responsive Grid | Auto-fill grid รองรับทุกขนาดหน้าจอ |
| ⚡ Lazy Loading | โหลดรูปแบบ Lazy เพื่อประสิทธิภาพที่ดีขึ้น |

## 📁 โครงสร้างโปรเจก

```
Certificates-Competitions-Activities-main/
├── index.html              # หน้าหลัก (Single Page)
├── certificates/
│   ├── Certificate1.png
│   ├── Certificate2.png
│   ├── Certificate3.png
│   ├── Certificate4.png
│   ├── Certificate5.png
│   └── Startup 2025.jpg
├── My Competitions/
│   ├── 2025.jpg
│   └── 2026.jpg
└── Activities/
    ├── Accepting younger siblings1.jpg
    ├── Accepting younger siblings2.jpg
    ├── Staff Open house 2025_1.jpg
    └── Staff Open house 2025_2.jpg
```

## 📊 สรุปเนื้อหา

| หมวด | จำนวน |
|-----|------|
| 📜 Certificates | 6 รายการ |
| 🏆 Competitions | 2 รายการ |
| 🎯 Activities | 4 รายการ |
| **รวม** | **12 รายการ** |

## 🛠️ Tech Stack

- **HTML5** — Single Page, Semantic Markup
- **CSS3** — CSS Variables, Animation (`fadeUp`, `scaleUp`), Glassmorphism Header
- **Vanilla JavaScript** — Tab Switching, Lightbox, Keyboard Events
- **Inter** (Google Fonts) — ฟอนต์หลัก

## 🚀 วิธีใช้งาน

1. Clone หรือดาวน์โหลดโปรเจก
2. เปิดไฟล์ `index.html` ในเบราว์เซอร์
3. ไม่ต้องติดตั้งอะไรเพิ่ม — ทำงานได้ทันที

## ➕ การเพิ่มรูปใหม่

1. วางไฟล์รูปในโฟลเดอร์ที่ต้องการ (`certificates/`, `My Competitions/`, `Activities/`)
2. เพิ่ม `<div class="card">` ใหม่ใน `index.html` ในส่วนที่ถูกต้อง
3. อัปเดตตัวเลข badge บน Tab และ `section-count`

---

**© 2026 Kittiphong Toadonthong** | [GitHub](https://github.com/kittiphongkubkub)
