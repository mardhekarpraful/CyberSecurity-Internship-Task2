# 📄 Phishing Analysis Report

## 🎯 Email Overview

**Subject:** Pontos Livelo - Resgate Agora  
**Sender Display Name:** Banco do Bradesco (Livelo)  
**Sender Email Address:** suspicious@blog1seguimentmydomaine2bra.me  
**Email Format:** HTML-based email with urgent language and external links

---

## 🔎 Key Indicators of Phishing

### 1. 🧑‍💻 Spoofed Sender Address
- **Claimed Identity:** Banco do Bradesco
- **Actual Email Domain:** `blog1seguimentmydomaine2bra.me`
- **Legitimate Domain (Expected):** `bradesco.com.br`
- **Indicator:** Sender domain is clearly not associated with Bradesco. Highly suspicious.

---

### 2. 📨 Email Header Anomalies
- **SPF/DKIM/DMARC:** Failed or not aligned
- **Reply-To Address:** Same as sender (non-legitimate)
- **Online Tools Used:** Google Admin Toolbox, MXToolbox
- **Conclusion:** Header data suggests spoofing and lack of verification mechanisms.

---

### 3. 🌐 Mismatched or Suspicious URLs
- **Displayed Link:** Resgatar Agora → `https://blog1seguimentmydomaine2bra.me/`
- **Issue:** URL does not match branding, uses unrelated domain
- **Method of Detection:** Hover over links revealed mismatched domains

---

### 4. ⚠️ Urgent & Manipulative Language
- **Phrases Found:**
  - “expiram HOJE” (expire TODAY)
  - “evite a perda” (avoid loss)
  - “resgate agora mesmo” (redeem now)
- **Purpose:** To manipulate the recipient into acting impulsively

---

### 5. ✍️ Grammar & Typo Issues
- Found in:
  - "spe ling or grammar errors" (ironically referenced)
  - Other unnatural sentence flows
- Suggests low-quality content, typical of phishing emails

---

### 6. 📎 No Legitimate Attachments or Branding Validation
- No official logos loaded from trusted domains
- Image links point to unspecified sources (e.g., `header.png`, `icone-superior.png`)
- No HTTPS validation or security footers included

---

## 🧠 Social Engineering Tactics Used
- Brand impersonation (Bradesco, Livelo)
- Fear of loss (point expiration)
- Sense of urgency to bypass rational thinking
- Use of incentives (travel miles, discounts)

---

## 🏁 Conclusion

This email is a **confirmed phishing attempt** designed to trick users into clicking a fraudulent link by imitating a legitimate banking reward system. It combines technical spoofing with psychological manipulation.

---

## 🛠 Tools Used

- Google Admin Toolbox: Header Analysis  
- MXToolbox: Header & Domain Lookup  
- Browser Inspect Tool: Link preview & domain matching  
- Text Editor: Raw `.eml` inspection

---

## ✅ Recommendations

- Do **NOT** click on links or download attachments
- Report the email to your organization’s IT/SOC team
- Block the sender domain on your mail gateway
- Educate users about urgent reward-based phishing scams

