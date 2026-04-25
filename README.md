# Proje Başlığı / Project Title

## Genel Bakış / Overview

<details>
<summary> 🇹🇷 Türkçe İçerik (Açmak için tıklayın)</summary>

1. CLAUDE.md Dosyası Nasıl Yazılır?
Etkili bir CLAUDE.md dosyası 200 satırdan az olmalı, net ve yapılandırılmış olmalıdır. 

Adım 1: Otomatik Başlangıç (Önerilen)
Proje dizininde claude init komutunu çalıştırarak Claude'un dosya yapısını analiz edip otomatik bir taslak oluşturmasını sağlayabilirsiniz. 

Adım 2: İçeriği Özelleştirme
CLAUDE.md dosyasını bir metin editörü ile açıp aşağıdaki yapıyı kullanarak düzenleyin:

```# Proje Hakkında

Bu proje [Proje Amacı] 

## Mimari ve Kurallar
- Proje yapısı `src/` klasöründe bulunur.
- UI bileşenleri için React ve Tailwind CSS kullanılır.
- Kodlar `camelCase` standartlarına uygun yazılmalıdır.

## Önemli Komutlar
- `npm run dev`: Geliştirme sunucusunu başlatır.
- `npm run test`: Testleri çalıştırır.

## Kısıtlamalar
- @rules/security.md dosyasındaki kurallara uyun.
- API anahtarlarını asla commit etmeyin.

## Dosya Yapısı
- `src/components/` - Yeniden kullanılabilir bileşenler.
- `src/hooks/` - Özel React hook'ları.
```
Adım 3: İpuçları
Ayrıntılı Dokümantasyon: Çok uzun talimatlar için @import veya @@ işaretlerini kullanarak diğer Markdown dosyalarını bağlayın (Ör: @@ docs/architecture.md).
Kurallar: IMPORTANT etiketi ile kritik kuralları belirtin.
İlişkiyi Yönet: Dosyada CLAUDE-Arşiv.md kullanarak eski kuralları temiz tutun. 


</details>

---

<details>
<summary> 🇺🇸English Content (Click to expand)</summary>

**1. How to Write a CLAUDE.md File?**
An effective CLAUDE.md file should be less than 200 lines, clear and structured.

**Step 1: Auto-Start (Recommended)**
By running the `claude init` command in the project directory, you can have Claude analyze the file structure and automatically generate a draft.

**Step 2: Customize the Content**
Open the CLAUDE.md file with a text editor and edit it using the following structure:

```markdown
# About the Project

This project [Project Purpose]

## Architecture and Rules
- The project structure is located in the `src/` folder.
- React and Tailwind CSS are used for UI components.
- Code must be written following `camelCase` standards.

## Important Commands
- `npm run dev`: Starts the development server.
- `npm run test`: Runs the tests.

## Restrictions
- Follow the rules in the @rules/security.md file.
- Never commit API keys.

## File Structure
- `src/components/` - Reusable components.
- `src/hooks/` - Custom React hooks.
```

**Step 3: Tips**

- **Detailed Documentation:** For very long instructions, link other Markdown files using `@import` or `@@` notation (e.g., `@@ docs/architecture.md`).
- **Rules:** Use the `IMPORTANT` tag to mark critical rules.
- **Manage History:** Use `CLAUDE-Archive.md` in the file to keep old rules clean.

</details>
