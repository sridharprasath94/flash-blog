# Flash Blog 🚀

A modern full-stack Flutter blogging application powered by Supabase.  
Users can create, explore, and manage blogs with authentication, image uploads, and real-time backend support.

---

## ✨ Features

- 🔐 Authentication (Sign up / Login with Supabase)
- 📝 Create and view blog posts
- 🖼️ Image upload using Supabase Storage
- 🧠 Clean state management using Riverpod
- ⚡ Reactive UI updates
- 🌐 Backend powered by Supabase (Auth, Database, Storage)

---

## 🏗️ Architecture

This project follows a scalable and maintainable structure:

- **Presentation Layer**
  - Flutter UI
  - Riverpod for state management

- **Domain Layer**
  - Business logic
  - Entities & use-cases

- **Data Layer**
  - Supabase integration (Auth, PostgREST, Storage)
  - Repository pattern

---

## 📦 Tech Stack

- **Flutter**
- **Riverpod**
- **Supabase**
  - Authentication
  - PostgreSQL Database
  - Storage (for images)
- **Freezed / JSON Serializable**
- **Clean Architecture (inspired)**

---

## 🚀 Getting Started

### 1. Clone the repository

```
git@github.com:sridharprasath94/FlashBlog-Flutter.git
```

### 2. Install dependencies

```
flutter pub get
```

### 3. Configure Supabase

Add your Supabase credentials in your project:

- `SUPABASE_URL`
- `SUPABASE_ANON_KEY`

You can configure them in your environment or directly in the project (recommended: use secure config).

---

### 4. Run the app

```
flutter run
```

---

## 📁 Project Structure

```
lib/
 ├── core/          # Common utilities
 ├── features/
 │    ├── auth/     # Authentication
 │    ├── blog/     # Blog feature
 ├── main.dart
```

---

## 🔮 Future Improvements

- ✏️ Edit & delete blog posts
- ❤️ Like & comment system
- 🔍 Search & filtering
- 🧪 Unit & widget testing
- 🌍 Offline support & caching

---

## 📄 License

This project is open-source and available under the MIT License.
