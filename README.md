# 📘 awstronaut club Members Submission Guide

Welcome to the awstronaut club! This project highlights K8SUG-certified awstronaut community members around the world. You must be fully AWS-certified and have officially claimed your awstronaut title before submitting.  
More info on [awstronaut](https://linkedin.com/company/awstronaut).

---

## 📥 How to Submit Your Profile

> 🚨 **Important:** You must [fork this repository](https://docs.github.com/en/get-started/quickstart/fork-a-repo), make your changes, and submit them via a **Pull Request (PR)**.  
> Please do **not** attempt to push changes directly to the main branch — it will be rejected automatically.

Your PR should include:

- A new entry at the bottom of `users.json`
- A custom avatar image (optional) added to the `avatars/` folder

---

### ✅ JSON Format

```json
{
  "name": "Yongkang He",
  "github": "yongkanghe",
  "certs": [
    "awstronaut",
    "kubestronaut"
  ],
  "city": "Melbourne",
  "country": "Australia",
  "date": "2024-07-01",
  "bio": "Founder @K8SUG | Creator @kubestrong & @awstronaut | kubestronaut | Akamai Advocate | AWS Builder | Azure MVP | Google GDE | Alibaba MVP | Multi-Cloud | Community Reach | DevRel | 100K Social Reach",
  "twitter": "yongkanghe",
  "linkedin": "yongkanghe",
  "website": "https://k8sug.ai",
  "avatar": "/avatars/yongkanghe.png"
}

📌 Field Descriptions
Field	Required	Description
name	✅	Full name or display name
github	✅	GitHub username (used for fallback avatar)
certs	✅	Certification codes (e.g., CKA, CKAD, awstronaut)
provider	✅	Certification provider (e.g., K8SUG, CNCF)
city	✅	City of residence
country	✅	Country (must match naming in the map)
date	✅	Certification date (YYYY-MM-DD)
bio	❌	Short description or personal motto
twitter	❌	Twitter handle (omit @)
linkedin	❌	LinkedIn username (not full URL)
website	❌	Personal or portfolio website
avatar	❌	Path to avatar image in /avatars/ folder

🖼️ Avatar Upload Guidelines
Place your avatar in the avatars/ folder (e.g., avatars/yourgithubusername.png)

File size must not exceed 500 KB

Recommended dimensions: 200×200 px (square images render best)

Allowed formats: .png or .jpg

If no avatar is uploaded, your GitHub profile picture will be used by default.

💡 Pull Request Tips
✅ Add your profile to the end of users.json

✅ Ensure your JSON is valid (use a JSON validator)

✅ Use a clear commit message, e.g.:

vbnet
复制
add: alicejohnson to certified list
🆘 New to GitHub or PRs?
Check out this official guide:
👉 GitHub Pull Request Guide

🙌 Thanks for contributing to the global awstronaut community!
Together we showcase the power of cloud certification and collaboration 💪☁️🌍
