# 🕵️‍♂️ Cryptosteganography

A multi-level project for hiding messages in images using steganography and cryptography techniques.

Steganografi ve kriptografi tekniklerini kullanarak görsellerde mesajları gizlemeye yönelik çok katmanlı bir proje.

---

## 📦 Project Overview / Projeye Genel Bakış

<details>
<summary>EN English Description</summary>

### 🔹 Easy Level – LSB (Least Significant Bit)
- Classic LSB technique.
- No encryption applied.
- Demonstrates basic steganography.

### 🔸 Medium Level – XOR + LSB
- Message is encrypted with a user-defined key using XOR logic.
- Encrypted data is embedded in the image using LSB.
- Balances simplicity and obscurity.

### 🔴 Hard Level – AES + LSB
- AES-256-GCM encryption.
- Requires AES key in hex to decrypt.
- Real-world security level.

Each level is implemented in a **single Jupyter notebook** with both hiding and revealing steps.

</details>

---

<details>
<summary>TR Türkçe Açıklama</summary>

### 🔹 Kolay Seviye – LSB (En Önemsiz Bit)
- Klasik LSB tekniği kullanılır.
- Şifreleme uygulanmaz.
- Temel steganografiyi gösterir.

### 🔸 Orta Seviye – XOR + LSB
- Mesaj, kullanıcı tanımlı bir anahtarla XOR mantığı kullanılarak şifrelenir.
- Şifrelenmiş veri, LSB ile görsele gömülür.
- Basitlik ve gizlilik dengesi sağlar.

### 🔴 Zor Seviye – AES + LSB
- AES-256-GCM şifreleme kullanılır.
- Şifre çözme için hex formatında AES anahtarı gerekir.
- Gerçek dünya güvenlik seviyesi sunar.

Her seviye hem mesaj gizleme hem çözme adımlarını içeren **tek bir Jupyter dosyası** ile sunulmuştur.

</details>

---

## 🧭 Quick Access

| 📂 Seviye / Level | TR Türkçe | EN English |
|----------|------------|-------------|
| 🔹 Kolay / Easy  | [Kolay.ipynb](Kolay.ipynb) | [Easy.ipynb](Easy.ipynb) |
| 🔸 Orta / Medium | [Orta.ipynb](Orta.ipynb) | [Medium.ipynb](Medium.ipynb) |
| 🔴 Zor / Hard  | [Zor.ipynb](Zor.ipynb) | [Hard.ipynb](Hard.ipynb) |



## 🧑‍💻 Prepared by
Project developed by Yiğit Yücel

```bash
