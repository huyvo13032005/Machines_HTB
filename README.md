# HackTheBox Writeups - Võ Quốc Huy

Repository này chứa các writeup cá nhân của tôi khi giải các machine trên HackTheBox.
Mục tiêu: luyện tập **Penetration Testing**, **Privilege Escalation**, và **Enumeration**.

> ⚠️ Các writeup chỉ mang tính chất học tập. Không sử dụng vào mục đích trái phép.

---

## 📌 Thông tin

* Platform: HackTheBox
* Author: Võ Quốc Huy
* Focus: OSCP / eJPT / Practical Pentesting
* Tools: nmap, gobuster, ffuf, burpsuite, linpeas, winpeas,...

---

## 📂 Danh sách Machine

| Machine | Difficulty | OS      | Status | Writeup           |
| ------- | ---------- | ------- | ------ | ----------------- |
| Lame    | Easy       | Linux   | ✅      | [View](./Lame)    |
| Blue    | Easy       | Windows | ✅      | [View](./Blue)    |
| Nibbles | Easy       | Linux   | ✅      | [View](./Nibbles) |

---

## 🧠 Methodology

Các bước tôi sử dụng khi làm machine:

1. Enumeration
2. Foothold
3. Privilege Escalation
4. Post Exploitation
5. Lessons Learned

---

## 🛠️ Tools thường dùng

```
nmap
gobuster
ffuf
burpsuite
netcat
linpeas
winpeas
pspy
```

---

## 📖 Format Writeup

Mỗi machine sẽ có cấu trúc:

```
Machine_Name/
 ├── README.md
 ├── screenshots/
 └── exploit/
```

---

## 🧪 Example Writeup Structure

### Enumeration

```
nmap -sC -sV -p- 10.10.10.X
```

### Foothold

* phát hiện service
* exploit vulnerability
* lấy shell

### Privilege Escalation

* kiểm tra sudo
* tìm SUID
* cronjob

### Root

```
whoami
root
```

---

## 🎯 Mục tiêu

* Hoàn thành tất cả Easy machines
* Tiếp tục Medium → Hard
* Chuẩn bị OSCP

---

## 📬 Contact

* GitHub: https://github.com/yourusername
* HackTheBox: https://app.hackthebox.com/profile/yourid
