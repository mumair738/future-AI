✨🚀 Future AI – Next-Gen Web3 Wallet Connect App
<p align="center"> <img src="https://github.com/mumair738/future-AI/assets/00000000/futuristic.gif" width="600"/> </p> <p align="center"> <b><i>A futuristic Web3 Authentication & Wallet Connect Platform powered by Next.js, Wagmi, and WalletConnect.</i></b> </p>
🌈⚡ Features (Animated Highlights)

💠 Instant WalletConnect v2 — MetaMask, Rainbow, Coinbase, Trust, all supported.
💠 Ultra-smooth AppKit UI — animated modal + transitions
💠 Next.js 14 App Router — fast, optimized, production-ready
💠 Message Signing + Account Detection
💠 Highly scalable architecture
💠 Deployed on Vercel with auto-builds

🧬 Tech Stack
<table align="center"> <tr> <td align="center"><img src="https://skillicons.dev/icons?i=nextjs" width="55"><br>Next.js 14</td> <td align="center"><img src="https://skillicons.dev/icons?i=react" width="55"><br>React 18</td> <td align="center"><img src="https://skillicons.dev/icons?i=ts" width="55"><br>TypeScript</td> <td align="center"><img src="https://skillicons.dev/icons?i=vercel" width="55"><br>Vercel</td> <td align="center"><img src="https://walletconnect.com/walletconnect-logo.svg" width="55"><br>WalletConnect</td> <td align="center"><img src="https://raw.githubusercontent.com/wagmi-dev/.github/main/assets/logo.svg" width="55"><br>Wagmi</td> </tr> </table>
🔮 Project Architecture (Glow Style)
future-ai/
│── app/               # App Router pages
│── config/            # Wagmi & AppKit configs
│── components/        # UI Components
│── public/            # Assets
│── .env.local         # WC Project ID
│── package.json
│── README.md

🔧 Installation (Magic Setup)
git clone https://github.com/mumair738/future-AI.git
cd future-AI
npm install


Add your environment variable:

NEXT_PUBLIC_WALLETCONNECT_PROJECT_ID=your_project_id_here


Run app:

npm run dev

🌐 Deployment (Animated Vercel Flow)
<p align="center"> <img src="https://github.com/mumair738/future-AI/assets/00000000/vercel-deploy.gif" width="600"/> </p>

Connect GitHub → Vercel

Add ENV in Settings

Deploy → Auto-live

Enjoy the magic ✨

🛡️ Environment Variables
Key	Purpose
NEXT_PUBLIC_WALLETCONNECT_PROJECT_ID	WalletConnect Cloud Project ID

Get one:
👉 https://cloud.walletconnect.com/

🎛️ Code Example – AppKit Provider
<AppKitProvider
  projectId={process.env.NEXT_PUBLIC_WALLETCONNECT_PROJECT_ID!}
  networks={wagmiAdapter.networks}
>
  {children}
</AppKitProvider>

🔥 Demo Preview (Animated Button)
<p align="center"> <a href="https://future-ai.vercel.app" target="_blank"> <img src="https://img.shields.io/badge/🚀 LIVE DEMO-00d1ff?style=for-the-badge&logo=vercel" /> </a> </p>
🦾 Contributing

Feel free to contribute, fix issues, or request new features 💡
Every PR is welcome!

🧠 License

MIT License © 2025 Future-AI
