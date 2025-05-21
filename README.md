# Payglen

**Payglen** is a secure and scalable **payment gateway** and **money transfer platform** built to serve Africa and beyond. Developed by [Stemgon (Pty) Ltd](https://stemgon.co.za), Payglen empowers individuals, businesses, and developers with the ability to send, receive, and manage money seamlessly via API, mobile, and web.

> 🌍 Fast. 💸 Secure. 🔌 Developer-Friendly.

---

## 🔐 Key Features

- 💳 **Payment Gateway**
  - Accept debit, credit, and mobile wallet payments
  - Support for PayFast, Ozow, Stripe, and more
  - Seamless merchant onboarding

- 💸 **Money Transfer**
  - Instant P2P transfers locally and cross-border
  - Integration with local banks and mobile money platforms
  - Trackable transaction history

- 📱 **API & SDK Access**
  - RESTful APIs with sandbox environment
  - Easy-to-use SDKs for Python, JavaScript, and more
  - Webhooks and secure callback mechanisms

- ⚙️ **Merchant Dashboard**
  - Real-time analytics and reports
  - User management and settlement tools

- 🔒 **Enterprise-Grade Security**
  - PCI DSS compliance ready
  - Tokenized transactions
  - Built-in fraud detection and AML mechanisms

---

## 📦 Tech Stack

- **Frontend:** React.js, Tailwind CSS
- **Backend:** Django, Django REST Framework
- **Database:** PostgreSQL, Redis (caching, queueing)
- **Messaging:** RabbitMQ / Celery
- **Payments Integration:** PayFast, Ozow, Stripe, local banking APIs
- **Infrastructure:** Docker, AWS, GitHub Actions, Terraform

---

## 🚀 Getting Started

> This section assumes you have `Python`, `Docker`, and `Git` installed.

```bash
# Clone the repo
git clone https://github.com/stemgon/payglen.git
cd payglen

# Spin up dev environment
docker-compose up --build


## 🧪 API Documentation
```bash
http://localhost:8000/api/docs/
# Alternatively, visit the hosted version
https://api.payglen.com/docs
```
