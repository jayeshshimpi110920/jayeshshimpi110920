- 👋 Hi, I’m @jayeshshimpi110920
- ❤️ to build
- 📫 reach to me --> @Jayeshshimpi1109 on LinkedIn

<!---
jayeshshimpi110920/jayeshshimpi110920 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

Subject: Responsible Disclosure: Exposed reCAPTCHA and Google Maps API Key Found on Your Site

Dear [Company Name] Security Team,

I hope you're doing well. I wanted to inform you about a potential vulnerability I found on your website [website URL].

While reviewing your website's frontend code, I discovered that your **reCAPTCHA secret key** and **Google Maps API key** are exposed in the JavaScript (Bootstrap data). Specifically, these sensitive keys are visible in the `BOOTSTRAP_DATA` object in the page source.

### Vulnerability Details:
- **Exposed reCAPTCHA Secret Key**: This could allow an attacker to bypass your CAPTCHA system or misuse the key for malicious purposes.
- **Exposed Google Maps API Key**: This key is public, but its unrestricted use could lead to abuse and additional costs.

### Steps to Reproduce:
1. Visit [URL].
2. Open the developer tools and inspect the source code.
3. Look for the `BOOTSTRAP_DATA` object and observe the exposed keys.

### Impact:
- **reCAPTCHA secret key** exposure can allow malicious actors to bypass CAPTCHA verifications.
- **Google Maps API key** exposure can result in unauthorized usage, potential misuse, and additional costs for your Google account.

### Recommendations:
- Please rotate the secret key and apply proper restrictions on the API keys (e.g., restrict usage to specific IP addresses or domains).
- Review the security of your frontend code to ensure sensitive data is not exposed.

Please let me know if you need further information or clarification. I am happy to assist in resolving this issue.

Best regards,
[Your Name or Handle]
[Optional: Bug Bounty or Security Researcher Profile Link]


