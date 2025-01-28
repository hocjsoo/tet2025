# Happy New Year 2025

Một trang web chúc mừng năm mới 2025 được xây dựng bằng HTML, CSS, JS thuần .

## Tính năng

- Giao diện Tết 🎋
- Phát nhạc 🎵
- Hiệu ứng hoa đào rơi 🌸
- Phát lì xì 🧧
- Xin lì xì 💰

## Tuỳ chỉnh

### 1. Thay đổi tin nhắn chúc Tết, phát lì xì

```javascript
const chucMungMessages = [
  '🎉 Chúc mừng năm mới! Chúc bạn một năm tràn đầy niềm vui...',
  '🌸 Tết đến xuân về, chúc bạn vạn sự như ý...',
  // Thêm hoặc sửa tin nhắn tại file script.js
];
```

### 2. Thay đổi tin nhắn xin lì xì

```javascript
const lixiMessages = [
  'Mình xin lì xì 💲',
  'Xin 10k nhé 💵',
  // Thêm hoặc sửa tin nhắn tại file script.js
];
```

### 3. Cấu hình QR Code xin lì xì

```javascript
// Đường dẫn QR
const filePathQR = './assets/qr/qr.jpg'; // Thay đổi đường dẫn
// Bật/tắt QR
const showQR = false; // true: bật, false: tắt
// Tỷ lệ xuất hiện QR (40%)
const hasQR = showQR ? Math.random() < 0.4 : false;
```

### 4. Thay nhạc

```javascript
// thay đổi đường dẫn nhạc ở file index.html
<source src="./assets/audio/nhuhoamuaxuan-wrenEvans.mp3" type="audio/mp3" />
```

## Deploy web

Có thể deploy web bằng nhiều cách khác nhau như : GitHubPages, [Netlify](https://www.netlify.com), [Vercel](https://vercel.com), [Render](https://render.com/)
‣整ੴ‣整㉴㈰ਵ‣〲㔲整ੴ