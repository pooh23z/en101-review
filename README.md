# EN101 Final Exam Review — Cozy Study Buddy

> เว็บแอปติวสรุปเนื้อหาและทำข้อสอบจำลองเตรียมสอบปลายภาควิชา EN101 (Unit 1 – 6) ตรงตามเอกสาร English Clinic (Weeks 12–13)

🌐 **Live Website:** [https://en101review.vercel.app](https://en101review.vercel.app)

---

## 🌟 ฟีเจอร์หลัก (Key Features)

1. **📚 ห้องเรียน & สรุปไวยากรณ์ (Grammar & Vocab Units 1–6):**
   - สรุปกฎไวยากรณ์สำคัญและจุดดักคะแนนในข้อสอบ (เช่น 12 Stative Verbs, Zero Conditional, When vs. While, -ing vs. -ed Adjectives, Present Perfect, Comparison of Nouns, Would you mind + V-ing)
   - คลังคำศัพท์ 92 คำ ครบทุกหมวดหมู่ พร้อมเสียงอ่านสำเนียงภาษาอังกฤษธรรมชาติ (Web Speech API)
   - มินิเกมลากคำศัพท์วางในภาพ (Drag-and-Drop) และ Flashcards

2. **🎧 พาร์ทฟัง (Listening Lab - 5 Tracks / 15 ข้อ):**
   - จำลองข้อสอบการฟังภาษาอังกฤษเสมือนจริง 5 บทสนทนา/เรื่องเล่า
   - เครื่องเล่นเสียงคลื่นเสียงจำลอง (Audio Wave)
   - ปุ่มปรับสปีดเสียงแบบ Real-time: `x0.5`, `x0.75`, `x1.0`, `x1.25`
   - ปุ่มดู / ซ่อน Transcript บทสนทนา พร้อมไฮไลต์จุดสำคัญ
   - แบบฝึกหัดทดสอบความเข้าใจ 3 ข้อต่อแทร็ก พร้อมเฉลยละเอียด

3. **📄 พารากราฟบทอ่าน (Reading Lab - 5 Passages / 15 ข้อ):**
   - รวมบทอ่านภาษาอังกฤษเต็มเรื่องครบทั้ง 5 บทตามชีตสรุป:
     - Unit 1: *Are Video Games Educational?*
     - Unit 2: *Student Times – Embarrassing Experiences*
     - Unit 3: *Dress to Impress*
     - Unit 5: *Seven Wonders of the Natural World*
     - Unit 6: *Perspectives on Time (Germany vs. Italy)*
   - ปุ่มฟังเสียงอ่านพารากราฟทั้งเรื่อง (Audio Narration)
   - ปุ่มดู / ซ่อน คำแปลภาษาไทยสรุปใจความ
   - ข้อสอบจับใจความ 3 ข้อต่อเรื่อง พร้อมเฉลยชี้จุดในเนื้อหา

4. **💡 ตะลุยข้อสอบจำลอง (Rescue Buddy Quiz - 36 ข้อ):**
   - ข้อสอบจำลอง 36 ข้อ กระจายตัวเลือกสมดุล (A, B, C, D)
   - ระบบเลือกวิธีดูเฉลยเมื่อตอบผิด: **"อ่านเฉลย (ข้อความ)"** หรือ **"ฟังเสียงเฉลย 🔊"**

---

## 🛠️ เทคโนโลยีที่ใช้ (Tech Stack)

- **Frontend:** HTML5, CSS3, Vanilla JavaScript (Single Page Application)
- **Audio & TTS:** Web Speech API (`SpeechSynthesis`)
- **Hosting & Analytics:** Vercel Static Hosting & Vercel Web Analytics
- **Design:** Cozy Minimalist Typography (`IBM Plex Sans Thai`, `Inter`, `Fredoka`)

---

## 🚀 การติดตั้งและรันในเครื่อง (Local Setup)

สามารถเปิดไฟล์ `index.html` บนเว็บบราวเซอร์ (Chrome, Safari, Edge) ได้ทันทีโดยไม่ต้องติดตั้ง Dependency เพิ่มเติม หรือรัน Local Server:

```bash
# รันผ่าน Python Local HTTP Server
python3 -m http.server 8000
```

เปิดบราวเซอร์ไปที่ `http://localhost:8000`
