HỘI THI CÁN BỘ KIỂM TRA GIỎI - XÃ TRIỆU VIỆT VƯƠNG 2026

═══════════════════════════════════════════════
📂 TRONG GÓI:
═══════════════════════════════════════════════
1️⃣  index.html     - ỨNG DỤNG HỘI THI (bảo vệ OTP)
2️⃣  tao-otp.html   - ỨNG DỤNG TẠO MÃ OTP (CHỈ dùng local)

═══════════════════════════════════════════════
🔐 BẢO VỆ OTP:
═══════════════════════════════════════════════
• Mở index.html → trang đòi nhập mã OTP 6 số
• Mở tao-otp.html trên máy của bạn (local) để
  xem mã hiện tại - mã đổi mỗi 5 PHÚT
• Nhập đúng mã → phiên truy cập 24 GIỜ
  (tắt trình duyệt mở lại vẫn vào được nếu
  chưa quá 24h; quá 24h phải nhập lại OTP)
• Chấp nhận cả mã của chu kỳ VỪA hết hạn
  (tránh lệch giờ giữa 2 máy)
• tao-otp.html dùng qua GitHub Pages:
  https://trieuvietvuonghy.github.io/vongsokhao/tao-otp.html
  (hoặc mở local: http://localhost:8000/tao-otp.html)
  Hai file phải dùng CÙNG 1 khóa bí mật
  (đã cấu hình sẵn trong source)

═══════════════════════════════════════════════
🎮 index.html - CẤU HÌNH HỘI THI:
═══════════════════════════════════════════════
• 16 bộ câu hỏi × 7 câu, dùng đúng dữ liệu thật từ bộ 1→16
• Mỗi lượt thi: 2 đội • Sai 2 lần: tự công bố đáp án
• Bấm chuột vào đáp án A/B/C/D trên màn hình
• Nút 📚: mở panel chọn bộ hoặc Random 🎲 chọn ngẫu nhiên
  một bộ chưa thi; số hiển thị và nội dung là cùng một bộ
• Nút 🏁 Kết thúc: khi 2 đội thi xong
• Không dùng phím tắt - chỉ chuột
• Nút ⛶ (góc phải dưới): toàn màn hình

═══════════════════════════════════════════════
⚠️  CÁCH MỞ (phải qua web server):
═══════════════════════════════════════════════
KHÔNG double-click mở file HTML trực tiếp!

CÁCH 1 (Python):
  PowerShell tại thư mục này →
    python -m http.server 8000
  Mở trình duyệt: http://localhost:8000

CÁCH 2 (VS Code):
  Cài extension "Live Server" → chuột phải
   index.html → Open with Live Server

CÁCH 3 (Node.js):  npx serve

LƯU Ý: Giữ TẤT CẢ file trong CÙNG 1 thư mục!
