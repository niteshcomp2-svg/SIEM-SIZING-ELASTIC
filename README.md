# 🔍 Elastic SIEM Sizing Calculator

> A free, simple tool to estimate storage, compute, and node requirements for your Elastic SIEM deployment.

---

## 🤔 What is this tool?

If you are setting up Elastic SIEM (a security monitoring system) for your company,
you need to know:
- 💾 How much **storage / disk space** you need
- 🖥️ How many **servers (nodes)** to set up
- ⚡ How much **CPU and RAM** each server needs

This tool asks you a few simple questions and gives you all the answers instantly — **no sign-up, no cost, runs in your browser!**

---

## 🚀 How to Use It (Super Simple!)

### Option 1 — Use it directly online (easiest)
1. Go to link
2. Fill in the form
3. Click **Calculate Sizing**
4. See your results instantly! ✅

---

### Option 2 — Download and open on your computer
1. Click the green **`<> Code`** button on this page
2. Click **"Download ZIP"**
3. Unzip the folder on your computer
4. Open the file called **`index.html`** in any browser (Chrome, Firefox, Edge)
5. Fill in the form and click **Calculate Sizing** ✅

---

## 📋 What Information Do You Enter?

| Field | What it means | Example |
|---|---|---|
| 👥 Number of Employees | Total people in your company | 500 |
| 🌐 Network Devices | Firewalls, routers, switches | 50 |
| 🖥️ Servers / Endpoints | Computers and servers you monitor | 100 |
| ☁️ Cloud Sources | AWS, Azure, GCP connections | 3 |
| ⚡ Events Per Second (EPS) | How many log events happen per second | 2000 |
| 📦 Avg Log Size | Average size of one log event in bytes | 500 |
| 📅 Retention Period | How many days to keep logs | 90 days |
| 🗜️ Compression Ratio | How much Elastic compresses your data | 4x |
| 📈 Annual Growth | Expected growth in logs per year | 20% |
| 🏗️ Architecture | Type of cluster setup | Distributed |

---

## 📊 What Results Do You Get?

After clicking **Calculate**, you will see:

- 🟢 / 🟡 / 🔴 **Deployment Tier** — Small, Medium, or Large
- 📈 **Daily Ingest** — GB of logs ingested per day
- 💾 **Storage Required** — Total disk space needed
- 🖥️ **Node Table** — Number of servers, with CPU, RAM, and Disk for each
- 💡 **Recommendations** — Tips to set up your cluster properly

---

## 🏗️ Architecture Options Explained

| Option | Best For | Description |
|---|---|---|
| **Single Node** | Very small setups | Everything on 1 server — simple but limited |
| **Distributed** ⭐ | Most companies | Separate master, data, and Kibana nodes — recommended |
| **Hot-Warm-Cold** | Large enterprises | Tiered storage — saves cost for older data |

---

## 💡 Tips for Beginners

- ✅ If you don't know your EPS, start with **1000–2000** for a small company
- ✅ Always use at least **1 replica** in production (protects your data)
- ✅ **Distributed** architecture is recommended for most setups
- ✅ Add **20–30% extra disk** beyond what the tool recommends (just to be safe)
- ✅ Use **ILM (Index Lifecycle Management)** in Elastic to save costs automatically

---

## 🛠️ Tech Stack

This tool is built with plain, simple web technologies — no installation needed:

- **HTML** — structure of the page
- **CSS** — styling and design
- **JavaScript** — calculations and logic

---

## 📁 Project Files

```
siem-sizing-of-elastic/
│
├── index.html        ← The main calculator (open this in browser)
└── README.md         ← This file (project description)
```

---

## 🙋 Who is this for?

- 🔐 Security Engineers setting up Elastic SIEM
- 🏢 IT Admins planning infrastructure
- 🧑‍🎓 Students learning about SIEM and Elastic Stack
- 👨‍💻 Anyone curious about log infrastructure sizing!

---

## 🤝 Contributing

Found a bug or want to improve the tool? You're welcome to help!

1. Click **Fork** on the top right of this page
2. Make your changes
3. Click **Pull Request** to submit your improvement

---

## 📜 License

This project is open source and free to use under the **MIT License**.

---

## 👤 Author

NiteshAI

> ⭐ If this tool helped you, please give it a **Star** on GitHub!
