# 🏡 Ayala Land

A **Real Estate Web Application** built with a **Next.js frontend** and a **Node.js + Express + Prisma backend**.  
The app allows users to browse, manage, and interact with real estate listings, with secure authentication, cloud storage, and a modern responsive UI.

---

## 🚀 Tech Stack

### **Frontend (Next.js 15)**

- ⚛️ React 19
- 🎨 TailwindCSS + Tailwind Animate
- 🎭 Framer Motion
- 🗺 Mapbox GL
- 🛠 Radix UI + Lucide Icons
- 📂 Filepond (Image Uploads)
- 🔑 Redux Toolkit for state management

### **Backend (Node.js + Express + Prisma)**

- 🟢 Express.js
- 🛡 Helmet, CORS, Morgan for security & logging
- 🗄 Prisma ORM (with PostgreSQL/MySQL/SQLite support)
- ☁️ AWS SDK (S3 storage for file uploads)
- 🔐 JWT Authentication
- 📦 Multer (file handling)

---

## 📂 Project Structure

ayala-land/
│── backend/ # Node.js + Express + Prisma API
│ ├── src/ # Application source code
│ ├── prisma/ # Prisma schema & seed
│ ├── package.json
│
│── frontend/ # Next.js 15 App
│ ├── src/ # Pages, components, features
│ ├── public/ # Static assets
│ ├── package.json
│
│── README.md

---

## ⚙️ Installation & Setup

### **1. Clone the Repository**

```bash
git clone https://github.com/your-username/ayala-land.git
cd ayala-land
```

```
cd backend
npm install


DATABASE_URL="your_database_connection_url"
JWT_SECRET="your_secret_key"
AWS_ACCESS_KEY_ID="your_aws_key"
AWS_SECRET_ACCESS_KEY="your_aws_secret"
AWS_S3_BUCKET="your_bucket_name"


npx prisma migrate dev
npm run seed


npm run dev
```

<br/>
<br/>

# Frontend Setup

```
cd ../frontend
npm install

NEXT_PUBLIC_API_URL="http://localhost:5000"  # Backend API
NEXT_PUBLIC_MAPBOX_TOKEN="your_mapbox_token"

npm run dev
```
