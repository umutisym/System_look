# System_look
# 🖥️ Sistem Bilgi Aracı

Python ile geliştirilmiş, terminal üzerinden sistem komutlarını çalıştırmanıza 
ve çıktılarını düzenli şekilde görmenizi sağlayan basit ve interaktif bir 
komut satırı aracıdır.

## ✨ Özellikler

- 🔧 Kullanıcıdan komut girişi alarak doğrudan sisteme iletir
- 📤 Komut çıktısını (`stdout`) ve hata mesajlarını (`stderr`) ayrı ayrı gösterir
- ✅ Komutun başarılı olup olmadığını `returncode` ile kontrol eder
- 🔁 `q` yazana kadar komut çalıştırmaya devam eder
- 🚫 Boş girişleri yakalayarak kullanıcıyı uyarır

## 📦 Gereksinimler

- Python 3.6 veya üzeri
- Ek bir kütüphane gerekmez (yalnızca standart kütüphaneler kullanılmıştır)

## 🚀 Kurulum

```bash
git clone https://github.com/kullanici-adin/sistem-bilgi-araci.git
cd sistem-bilgi-araci
python main.py
