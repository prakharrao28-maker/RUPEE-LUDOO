# 📱 Blank Android App (React + Capacitor)

This is a blank starter project for creating Android apps using **React + Capacitor**.

## 🚀 How to Run Locally
1. Install dependencies:
   ```bash
   npm install
   ```
2. Run dev server:
   ```bash
   npm run dev
   ```
3. Add Android platform and build:
   ```bash
   npx cap add android
   npx cap copy
   npx cap open android
   ```

## 🧩 GitHub Actions (Automatic Build)
- Push code to GitHub
- Go to **Actions tab**
- Run the workflow `Build Android APK (Blank App)`
- Download your built APK from the **Artifacts** section
