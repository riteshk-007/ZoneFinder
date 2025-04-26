# ZoneFinder 🚀

ZoneFinder is a professional Demand-Supply Stock Scanner SaaS built for traders and investors. 
Easily scan stocks across multiple timeframes and detect approaching Demand or Supply Zones. 
Save time, get smart alerts, and gain an edge in the market.

---

## ✨ Features

- 🔍 Multi-Timeframe Stock Scanning (Yearly, Quarterly, Monthly, Weekly, Daily)
- 🎯 Demand & Supply Zone Detection
- 📈 Distance from Zone Calculation (in %)
- 📨 Real-Time Alerts (Email, SMS, WhatsApp)
- 🔒 Secure User Authentication (Google, Facebook, Twitter, Phone)
- ⚙️ Admin Panel for User Management
- 🎨 Light and Dark Themes
- 💳 Subscription Plans (Monthly, Quarterly, Half-Yearly, Yearly)
- 🏰 Discount Vouchers and Promo Codes
- 🔐 Activity Monitoring (Admin Only)

---

## 📚 Tech Stack

| Tech         | Details                           |
|:-------------|:-----------------------------------|
| Frontend     | Next.js 14 (App Router)            |
| Backend      | Next.js API Routes (REST API)      |
| Database     | PostgreSQL                        |
| ORM          | Prisma ORM                         |
| Authentication| NextAuth.js                      |
| UI Framework | TailwindCSS + shadcn/ui            |
| Hosting      | Vercel (Frontend) + Supabase/Railway (Database) |

---

## 🛠️ Setup Instructions

### 1. Clone the repository
```bash
git clone https://github.com/riteshk-007/zonefinder.git
cd zonefinder
```

### 2. Install dependencies
```bash
npm install
# or
yarn install
```

### 3. Setup Environment Variables
Create a `.env` file in the root:
```env
DATABASE_URL=postgresql://username:password@localhost:5432/zonefinder
NEXTAUTH_SECRET=your_random_secret
NEXTAUTH_URL=http://localhost:3000
EMAIL_SERVER=smtp://user:pass@smtp.your-email.com:587
TWILIO_ACCOUNT_SID=your_twilio_sid
TWILIO_AUTH_TOKEN=your_twilio_token
```

### 4. Setup Prisma
```bash
npx prisma generate
npx prisma migrate dev --name init
```

### 5. Run the Development Server
```bash
npm run dev
# or
yarn dev
```

Visit `http://localhost:3000` to see ZoneFinder running locally! 🚀

---

## 📊 Database Schema Overview

- Users (Admin/User roles)
- Stocks List
- Demand/Supply Zones
- Subscriptions
- Alerts/Notifications
- User Activity Logs

---

## 🌟 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

## 🔥 Credits

Made with ❤️ by Ritesh 

---
