# Öğrenciler İçin Ücretsiz Domain / Free Domain for Students

## Türkçe 🇹🇷

### Evet, Öğrencilere Ücretsiz Domain Var! 🎓

GitHub Student Developer Pack aracılığıyla öğrenciler **ücretsiz domain** alabilir. Birden fazla seçenek mevcut!

---

## Ücretsiz Domain Seçenekleri

### 1. **Namecheap - .me Domain** ⭐ (En Popüler)

**Ne sunuyor:**
- 1 yıl ücretsiz .me domain
- 1 yıl ücretsiz SSL sertifikası
- DNS yönetimi
- Domain gizliliği (WHOIS protection)

**Nasıl alınır:**

1. **GitHub Student Developer Pack'i aktif edin**
   - Link: https://education.github.com/pack

2. **Namecheap teklifini bulun**
   - https://education.github.com/pack/offers sayfasında "Namecheap" araması yapın

3. **"Get access" butonuna tıklayın**
   - GitHub hesabınızla yetkilendirme yapın

4. **Namecheap'e yönlendirileceksiniz**
   - Öğrenci kuponu otomatik olarak hesabınıza eklenecek

5. **Domain arama yapın**
   - İstediğiniz ismi girin (örnek: yourname.me)
   - Domain müsaitse sepete ekleyin

6. **Checkout işlemini tamamlayın**
   - Öğrenci kuponu ile ödeme: $0.00
   - Ödeme bilgisi gerekmez (kupon tam indirim sağlar)

**Önemli notlar:**
- ✅ Sadece .me uzantılı domain'ler ücretsiz
- ✅ SSL sertifikası dahil
- ⏰ 1 yıl ücretsiz, sonrası normal fiyat
- 📧 Yenileme zamanı gelince e-posta bildirimi alırsınız

---

### 2. **Name.com - Herhangi Bir Domain**

**Ne sunuyor:**
- 1 yıl ücretsiz domain (herhangi bir uzantı)
- .com, .net, .org, .io, .dev, .tech ve daha fazlası
- Domain yönetim paneli

**Nasıl alınır:**

1. **GitHub Student Developer Pack'i aktif edin**

2. **Name.com teklifini bulun**
   - https://education.github.com/pack/offers sayfasında

3. **Teklifi aktif edin**
   - "Get access by connecting your GitHub account" butonuna tıklayın

4. **Name.com hesabı oluşturun**
   - GitHub ile bağlantıyı onaylayın

5. **Domain seçin**
   - İstediğiniz uzantıyı seçebilirsiniz (.com, .io, .dev, vb.)
   - Sepete ekleyin

6. **Öğrenci kuponu uygulayın**
   - Checkout sayfasında otomatik uygulanmalı
   - Değilse, GitHub Pack'ten aldığınız kodu girin

**Avantajlar:**
- ✅ Herhangi bir domain uzantısı seçebilirsiniz
- ✅ Popüler uzantılar dahil (.com, .io, .dev)
- ⏰ 1 yıl ücretsiz

---

### 3. **tech Domain**

**Ne sunuyor:**
- 1 yıl ücretsiz .tech domain
- Teknoloji odaklı domain uzantısı

**Nasıl alınır:**

1. GitHub Student Pack'te .tech domain teklifini bulun
2. Teklifi aktif edin
3. İstediğiniz .tech domain'i kaydedin

---

## Domain'i Nerede Kullanabilirsiniz?

### 🌐 **Web Sitesi Hosting**

Domain'inizi şu platformlarda kullanabilirsiniz:

1. **GitHub Pages** (Ücretsiz)
   - Static web siteleri
   - Portfolio, blog, proje sayfaları
   - yourname.me → GitHub Pages'e yönlendir

2. **Netlify** (Ücretsiz)
   - Modern web uygulamaları
   - Otomatik deployment
   - SSL sertifikası dahil

3. **Vercel** (Ücretsiz)
   - Next.js, React uygulamaları
   - Otomatik SSL
   - Hızlı deployment

4. **Heroku** (GitHub Pack'te ücretsiz)
   - Backend uygulamaları
   - Database destekli projeler

5. **DigitalOcean** (GitHub Pack'te $200 kredi)
   - VPS sunucu
   - Tam kontrol

### 📧 **E-posta Adresi**

Domain'iniz ile profesyonel e-posta:
- isminiz@yourname.me
- Zoho Mail (ücretsiz plan)
- ProtonMail (custom domain opsiyonel)

### 🚀 **Portföy ve Blog**

- Kişisel portföy sitesi
- Teknik blog
- Proje showcase
- Online CV/Resume

---

## Adım Adım: Domain'i GitHub Pages'e Bağlama

### 1. GitHub Pages Sitesi Oluşturun

```bash
# Yeni repository oluşturun
# Repository adı: username.github.io

# index.html dosyası ekleyin
echo "<h1>Merhaba Dünya!</h1>" > index.html

# Commit ve push
git add .
git commit -m "Initial commit"
git push
```

### 2. Domain DNS Ayarları

**Namecheap veya Name.com paneline gidin:**

1. **DNS yönetimine gidin**
   - "Manage Domain" → "Advanced DNS" veya "DNS Settings"

2. **A Record ekleyin:**
   ```
   Type: A Record
   Host: @
   Value: 185.199.108.153
   TTL: Automatic
   ```

3. **Alternatif A Record'lar ekleyin:**
   ```
   185.199.109.153
   185.199.110.153
   185.199.111.153
   ```

4. **CNAME Record (www için):**
   ```
   Type: CNAME
   Host: www
   Value: username.github.io
   TTL: Automatic
   ```

### 3. GitHub Repository Ayarları

1. Repository'nize gidin
2. **Settings** → **Pages**
3. **Custom domain** alanına domain'inizi girin: `yourname.me`
4. **Save** butonuna tıklayın
5. **Enforce HTTPS** seçeneğini aktif edin (birkaç dakika sonra)

### 4. Bekleyin ⏰

- DNS değişiklikleri 5 dakika - 48 saat arası yayılabilir
- Genellikle 10-30 dakika içinde aktif olur

---

## Sık Sorulan Sorular

### ❓ Hangi domain uzantısını seçmeliyim?

**Kişisel web sitesi için:**
- `.me` - Kişisel marka, portföy
- `.dev` - Geliştirici portföyü
- `.io` - Teknoloji projeleri
- `.com` - Genel kullanım, profesyonel

**Proje için:**
- `.app` - Mobil/web uygulamaları
- `.tech` - Teknoloji projeleri
- `.site` - Genel web siteleri

### ❓ 1 yıl sonra ne olur?

- Domain normal fiyattan yenilenebilir
- Yenilemezseniz, domain serbest kalır
- Önemliyse yenileyin, değilse yeni ücretsiz domain alabilirsiniz
- GitHub Student Pack aktifse, her yıl yeni ücretsiz domain alabilirsiniz

### ❓ Birden fazla ücretsiz domain alabilir miyim?

- ✅ Evet! Hem Namecheap hem Name.com'dan alabilirsiniz
- Her platform ayrı teklif sunar
- Aynı anda birden fazla domain'e sahip olabilirsiniz

### ❓ Domain'i transfer edebilir miyim?

- 60 gün sonra başka bir registrar'a transfer edebilirsiniz
- Transfer ücreti olabilir
- Genellikle 1 yıllık yenileme ile birlikte gelir

### ❓ Alt domain (subdomain) oluşturabilir miyim?

- ✅ Evet! Sınırsız alt domain oluşturabilirsiniz
- Örnek: blog.yourname.me, api.yourname.me
- DNS ayarlarından CNAME veya A record ekleyerek

### ❓ Domain gizliliği (WHOIS protection) var mı?

- ✅ Namecheap ile 1 yıl ücretsiz
- Kişisel bilgileriniz WHOIS sorgularında gizlenir
- Önerilir: Her zaman aktif tutun

---

## English 🇬🇧

### Yes, Students Get Free Domains! 🎓

Through the GitHub Student Developer Pack, students can get **free domains**. Multiple options available!

---

## Free Domain Options

### 1. **Namecheap - .me Domain** ⭐ (Most Popular)

**What you get:**
- 1 year free .me domain
- 1 year free SSL certificate
- DNS management
- Domain privacy (WHOIS protection)

**How to get it:**

1. **Activate GitHub Student Developer Pack**
   - Link: https://education.github.com/pack

2. **Find Namecheap offer**
   - Search for "Namecheap" on https://education.github.com/pack/offers

3. **Click "Get access" button**
   - Authorize with your GitHub account

4. **You'll be redirected to Namecheap**
   - Student coupon will be automatically added to your account

5. **Search for your domain**
   - Enter desired name (e.g., yourname.me)
   - Add to cart if available

6. **Complete checkout**
   - With student coupon: $0.00
   - No payment info needed (coupon provides full discount)

**Important notes:**
- ✅ Only .me domains are free
- ✅ SSL certificate included
- ⏰ 1 year free, then regular price
- 📧 You'll get email notification before renewal

---

### 2. **Name.com - Any Domain**

**What you get:**
- 1 year free domain (any extension)
- .com, .net, .org, .io, .dev, .tech and more
- Domain management panel

**How to get it:**

1. **Activate GitHub Student Developer Pack**

2. **Find Name.com offer**
   - On https://education.github.com/pack/offers

3. **Activate the offer**
   - Click "Get access by connecting your GitHub account"

4. **Create Name.com account**
   - Authorize GitHub connection

5. **Choose your domain**
   - Select any extension (.com, .io, .dev, etc.)
   - Add to cart

6. **Apply student coupon**
   - Should auto-apply at checkout
   - If not, enter code from GitHub Pack

**Advantages:**
- ✅ Choose any domain extension
- ✅ Popular extensions included (.com, .io, .dev)
- ⏰ 1 year free

---

### 3. **tech Domain**

**What you get:**
- 1 year free .tech domain
- Technology-focused domain extension

**How to get it:**

1. Find .tech domain offer in GitHub Student Pack
2. Activate the offer
3. Register your desired .tech domain

---

## Where Can You Use Your Domain?

### 🌐 **Website Hosting**

Use your domain with these platforms:

1. **GitHub Pages** (Free)
   - Static websites
   - Portfolio, blog, project pages
   - Point yourname.me → GitHub Pages

2. **Netlify** (Free)
   - Modern web applications
   - Automatic deployment
   - SSL certificate included

3. **Vercel** (Free)
   - Next.js, React applications
   - Automatic SSL
   - Fast deployment

4. **Heroku** (Free in GitHub Pack)
   - Backend applications
   - Database-backed projects

5. **DigitalOcean** ($200 credit in GitHub Pack)
   - VPS server
   - Full control

### 📧 **Email Address**

Professional email with your domain:
- yourname@yourname.me
- Zoho Mail (free plan)
- ProtonMail (custom domain optional)

### 🚀 **Portfolio and Blog**

- Personal portfolio site
- Technical blog
- Project showcase
- Online CV/Resume

---

## Step-by-Step: Connect Domain to GitHub Pages

### 1. Create GitHub Pages Site

```bash
# Create new repository
# Repository name: username.github.io

# Add index.html file
echo "<h1>Hello World!</h1>" > index.html

# Commit and push
git add .
git commit -m "Initial commit"
git push
```

### 2. Domain DNS Settings

**Go to Namecheap or Name.com panel:**

1. **Go to DNS management**
   - "Manage Domain" → "Advanced DNS" or "DNS Settings"

2. **Add A Record:**
   ```
   Type: A Record
   Host: @
   Value: 185.199.108.153
   TTL: Automatic
   ```

3. **Add alternative A Records:**
   ```
   185.199.109.153
   185.199.110.153
   185.199.111.153
   ```

4. **CNAME Record (for www):**
   ```
   Type: CNAME
   Host: www
   Value: username.github.io
   TTL: Automatic
   ```

### 3. GitHub Repository Settings

1. Go to your repository
2. **Settings** → **Pages**
3. Enter your domain in **Custom domain**: `yourname.me`
4. Click **Save**
5. Enable **Enforce HTTPS** (available after a few minutes)

### 4. Wait ⏰

- DNS changes can take 5 minutes - 48 hours to propagate
- Usually active within 10-30 minutes

---

## Frequently Asked Questions

### ❓ Which domain extension should I choose?

**For personal website:**
- `.me` - Personal brand, portfolio
- `.dev` - Developer portfolio
- `.io` - Tech projects
- `.com` - General use, professional

**For projects:**
- `.app` - Mobile/web applications
- `.tech` - Technology projects
- `.site` - General websites

### ❓ What happens after 1 year?

- Domain can be renewed at regular price
- If not renewed, domain becomes available
- If important, renew; otherwise get new free domain
- With active GitHub Student Pack, you can get new free domain each year

### ❓ Can I get multiple free domains?

- ✅ Yes! You can get from both Namecheap and Name.com
- Each platform offers separate deals
- You can own multiple domains simultaneously

### ❓ Can I transfer my domain?

- After 60 days, you can transfer to another registrar
- Transfer fee may apply
- Usually comes with 1-year renewal

### ❓ Can I create subdomains?

- ✅ Yes! Unlimited subdomains
- Example: blog.yourname.me, api.yourname.me
- Add CNAME or A record from DNS settings

### ❓ Is domain privacy (WHOIS protection) included?

- ✅ Free for 1 year with Namecheap
- Your personal info hidden from WHOIS queries
- Recommended: Always keep it active

---

## Yararlı Bağlantılar / Useful Links

- **GitHub Student Pack:** https://education.github.com/pack
- **Namecheap Education:** https://www.namecheap.com/github-student-developer-pack/
- **Name.com Students:** https://www.name.com/partner/github-students
- **GitHub Pages Docs:** https://docs.github.com/en/pages
- **Custom Domain Guide:** https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site

---

## İpuçları / Tips

### 🎯 **Domain Seçimi İpuçları / Domain Selection Tips**

1. **Kısa ve akılda kalıcı** - Short and memorable
2. **Yazılması kolay** - Easy to spell
3. **Telaffuzu açık** - Clear pronunciation
4. **Anlamlı** - Meaningful
5. **Rakam ve tire kullanmaktan kaçının** - Avoid numbers and hyphens

### 🔒 **Güvenlik İpuçları / Security Tips**

1. **Domain gizliliğini aktif edin** - Enable domain privacy
2. **İki faktörlü kimlik doğrulama** - Two-factor authentication
3. **Güçlü şifre kullanın** - Use strong password
4. **Otomatik yenilemeyi ayarlayın** - Set up auto-renewal (if keeping)

### 🚀 **Kullanım İpuçları / Usage Tips**

1. **Email adresi oluşturun** - Create professional email
2. **SSL sertifikasını aktif edin** - Enable SSL certificate
3. **Analytics ekleyin** - Add analytics (Google Analytics, Plausible)
4. **Sosyal medyada paylaşın** - Share on social media

---

**Son güncelleme / Last updated:** 2025-12-02

**Not:** Bu bilgiler GitHub Education ve domain sağlayıcılarının mevcut programlarına dayanmaktadır. Değişiklikler için resmi siteleri kontrol edin.

**Note:** This information is based on current GitHub Education and domain provider programs. Check official sites for any changes.
