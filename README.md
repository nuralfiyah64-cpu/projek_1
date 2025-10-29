# 🐍 PythonGame - Gamifikasi Pemrograman Python

Platform pembelajaran Python interaktif dengan sistem gamifikasi untuk siswa SMK. Belajar pemrograman Python dengan cara yang menyenangkan melalui 3 level tantangan.

## 🎯 Fitur Utama

### 📚 **3 Level Pembelajaran**
- **Beginner** - Dasar-dasar Python (variabel, tipe data, kontrol flow)
- **Medium** - Python menengah (fungsi, list, dictionary, file handling)
- **Hard** - Python lanjutan (OOP, error handling, algoritma kompleks)

### 🎮 **Sistem Gamifikasi**
- ✅ Sistem poin untuk setiap soal yang diselesaikan
- 🏆 Progress tracking untuk setiap level
- 🔓 Sistem unlock level berdasarkan completion
- 💡 Hint system untuk membantu siswa

### 👤 **User Management**
- 📝 Form registrasi dan login
- 📊 Dashboard personal dengan statistik pembelajaran
- 🏅 Tracking skor dan progress

### 💻 **Code Editor**
- 📝 Interactive code editor dengan syntax highlighting
- ▶️ Real-time code execution simulation
- 🔄 Reset code functionality
- 💬 Output display untuk melihat hasil kode

## 🛠️ Teknologi yang Digunakan

### Frontend
- **⚡ Next.js 15** - React framework dengan App Router
- **📘 TypeScript 5** - Type safety
- **🎨 Tailwind CSS 4** - Styling modern
- **🧩 shadcn/ui** - Component library berkualitas tinggi
- **🎯 Lucide React** - Icon library

### Backend
- **🗄️ Prisma ORM** - Database management
- **🔐 bcryptjs** - Password hashing
- **📡 API Routes** - RESTful API endpoints

### Database
- **📦 SQLite** - Local database untuk development

## 🚀 Quick Start

```bash
# Install dependencies
npm install

# Setup database
npm run db:push

# Seed database dengan levels dan questions
curl -X POST http://localhost:3000/api/seed

# Start development server
npm run dev
```

Buka [http://localhost:3000](http://localhost:3000) untuk melihat aplikasi.

## 📁 Struktur Proyek

```
src/
├── app/                    # Next.js App Router
│   ├── api/               # API Routes
│   │   ├── auth/          # Authentication endpoints
│   │   ├── dashboard/     # Dashboard data
│   │   └── seed/          # Database seeding
│   ├── dashboard/         # Dashboard page
│   ├── game/              # Game interface
│   └── page.tsx           # Landing page
├── components/
│   └── ui/                # shadcn/ui components
├── lib/
│   ├── db.ts              # Database client
│   └── utils.ts           # Utility functions
└── hooks/                 # Custom React hooks
```

## 🎮 Cara Penggunaan

### 1. Registrasi & Login
- Buka halaman utama
- Register akun baru dengan email dan password
- Login untuk mengakses dashboard

### 2. Dashboard
- Lihat progress pembelajaran
- Track skor dan level yang diselesaikan
- Pilih level yang ingin dimainkan

### 3. Game Interface
- Baca deskripsi soal
- Tulis kode Python di editor
- Jalankan kode untuk melihat hasil
- Gunakan hint jika kesulitan
- Selesaikan semua soal untuk unlock level berikutnya

## 📊 Database Schema

### Users
- Authentication data
- Progress tracking
- Score accumulation

### Levels
- 3 difficulty levels
- Question associations
- Progress relationships

### Questions
- Coding challenges
- Solutions and hints
- Point values

### User Progress
- Completion tracking
- Score per level
- Attempt history

## 🎯 Target Pengguna

Aplikasi ini dirancang khusus untuk:
- 👨‍🏫 **Guru SMK** - Mata pelajaran Pemrograman Web
- 🎓 **Siswa SMK** - Pembelajaran Python dasar hingga lanjutan
- 📚 **Self-learners** - Belajar Python secara mandiri

## 🌟 Fitur Pembelajaran

### Beginner Level (10 Soal)
- Hello World
- Variabel dan Tipe Data
- Operasi Aritmatika
- Input User
- Conditional Statements
- Loops
- List dan String Manipulation

### Medium Level (12 Soal)
- Functions
- List Comprehension
- Dictionary
- File Handling
- Exception Handling
- Lambda Functions
- Map dan Filter
- String dan List Methods

### Hard Level (8 Soal)
- Object-Oriented Programming
- Inheritance
- Polymorphism
- Decorators
- Generators
- Recursion
- Custom Exceptions
- Module System

## 🔧 Development

```bash
# Run linting
npm run lint

# Build for production
npm run build

# Start production server
npm start
```

## 🤝 Kontribusi

Proyek ini dikembangkan sebagai bagian dari implementasi kurikulum Pemrograman Web SMK dengan fokus pada:
- 📖 Pembelajaran interaktif
- 🎮 Gamifikasi edukasi
- 💻 Praktik coding langsung
- 📊 Progress tracking

## 📄 Lisensi

Projek ini dikembangkan untuk keperluan pendidikan. Silakan digunakan dan dimodifikasi sesuai kebutuhan pembelajaran.

---

Dibuat dengan ❤️ untuk pendidikan pemrograman di Indonesia 🇮🇩
