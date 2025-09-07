# 📸 Instagram Clone

Dự án **Instagram Clone** được xây dựng với:
- **Backend**: Node.js + Express + MongoDB
- **Frontend**: React.js + Vite
- **Cloudinary**: Lưu trữ ảnh

---

## 🚀 Cấu trúc dự án
```
.
├── backend      # Node.js + Express + MongoDB
├── frontend     # React.js + Vite
└── README.md
```

---

## ⚙️ Yêu cầu môi trường
- Node.js >= 18
- npm >= 9
- MongoDB (local hoặc Atlas)
- Tài khoản [Cloudinary](https://cloudinary.com/) để upload ảnh

---

## 📦 Cài đặt

### 1. Clone project
```bash
git clone https://github.com/quangnguyentan/insta_clone
cd insta_clone
```

### 2. Cài đặt dependencies
Chỉ cần chạy:
```bash
npm install
```

### 3. Cấu hình backend
Tạo file `.env` trong thư mục `backend` với nội dung:

```env
PORT=8080
SECRET_KEY=your_secret_key
MONGO_URI=your_mongodb_uri

# Cloudinary config
CLOUD_NAME=your_cloud_name
API_KEY=your_api_key
API_SECRET=your_api_secret

# Client URL
URL=http://localhost:5173
```

---

## 🚀 Chạy dự án

Chạy lệnh:
```bash
npm run dev
```

Cả **backend** và **frontend** sẽ chạy song song:
- Backend: [http://localhost:8080](http://localhost:8080)
- Frontend: [http://localhost:5173](http://localhost:5173)

---

## 🖼️ Tích hợp Cloudinary
Để upload ảnh, cần đăng ký tài khoản Cloudinary và lấy:
- `CLOUD_NAME`
- `API_KEY`
- `API_SECRET`  

Sau đó cập nhật vào file `.env` của **backend**.
