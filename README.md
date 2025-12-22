# VitalSpace Landing Page

Profesionální landing page pro službu ozonové sanitace prostoru.

## 📁 Struktura projektu

```
VitalSpace/
├── index.html              # Hlavní stránka (modulární struktura)
├── pages/                  # Podstránky programů
│   ├── reset.html          # Reset prostoru - jednorázová sanitace
│   ├── prevent.html        # Prevent program - pravidelná sanitace
│   ├── clinic.html         # Clinic Standard - pro zdravotnictví
│   └── rental.html         # Pronájem zařízení
├── private/                # Interní dokumenty (není na GitHubu)
│   └── protokol-vzor.html  # Vzorový protokol sanitace
├── css/
│   └── styles.css          # Všechny styly (včetně podstránek)
├── js/
│   └── main.js             # JavaScript funkce
├── images/                 # Složka pro obrázky
│   ├── hero-image.jpg      # Hero obrázek (1200×600px)
│   ├── favicon.svg         # Favicon
│   ├── icons/              # SVG ikony pro sekce
│   │   ├── bacteria.svg
│   │   ├── chemical.svg
│   │   ├── sleep.svg
│   │   └── ...
│   └── products/           # Fotky produktů
│       ├── ozon-cleaner-pro.jpg
│       ├── ozon-clean-up.jpg
│       └── ozon-clean-box.jpg
├── vitalspace-landing.html # Původní verze (záloha)
├── vitalspace-landing-2.html # Verze 2 (záloha)
├── program-*.html          # Původní podstránky (záloha)
├── .gitignore
└── README.md
```

## 🖼️ Obrázky k doplnění

Stránka obsahuje placeholdery pro obrázky. Nahraďte je skutečnými soubory:

### Hero sekce
- `images/hero-image.jpg` - Hlavní obrázek (doporučeno 1200×600px)

### Ikony (64×64px, SVG doporučeno)
- `images/icons/bacteria.svg` - Bakterie
- `images/icons/chemical.svg` - Chemie
- `images/icons/sleep.svg` - Spánek
- `images/icons/hospital.svg` - Nemocnice
- `images/icons/house-damage.svg` - Poškození
- `images/icons/productivity.svg` - Produktivita
- A další dle potřeby...

### Produkty
- `images/products/ozon-cleaner-pro.jpg` - OZON CLEANER PRO I PLUS
- `images/products/ozon-clean-up.jpg` - OZON CLEAN UP
- `images/products/ozon-clean-box.jpg` - OZON CLEAN BOX – DRY

## 📝 Formulářový widget

V sekci `#form` je připravené místo pro vložení externího formulářového widgetu.

### Podporované služby:
- **Typeform** - `<div data-tf-widget="..."></div>`
- **Tally** - `<iframe src="https://tally.so/embed/..."></iframe>`
- **HubSpot** - HubSpot form embed code
- **Google Forms** - `<iframe src="https://docs.google.com/forms/..."></iframe>`
- **Jotform** - Jotform embed code

### Jak vložit widget:
1. Otevřete `index.html`
2. Najděte sekci `<!-- FORM WIDGET PLACEHOLDER -->`
3. Nahraďte `<div class="form-widget-placeholder">...</div>` kódem vašeho widgetu

Alternativně můžete odkomentovat fallback formulář v HTML.

## 🚀 Deployment na GitHub Pages

1. Vytvořte nový repozitář na GitHubu
2. Inicializujte git a pushněte:

```bash
cd VitalSpace
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/USERNAME/vitalspace.git
git push -u origin main
```

3. V nastavení repozitáře:
   - Settings → Pages
   - Source: Deploy from a branch
   - Branch: main / (root)
   - Save

4. Stránka bude dostupná na: `https://USERNAME.github.io/vitalspace/`

## 🎨 Barevné schéma

```css
--primary-blue: #0066FF;
--dark-blue: #001F3F;
--cyan: #00D4FF;
--light-cyan: #6FEFFF;
--white: #FFFFFF;
--light-gray: #F5F9FF;
--medium-gray: #E8F1FF;
--text-dark: #1A2332;
--text-gray: #4A5568;
```

## 📱 Responzivita

Stránka je plně responzivní a optimalizovaná pro:
- Desktop (1200px+)
- Tablet (768px - 1199px)
- Mobile (< 768px)

## ✍️ Autor

Návrh & code: **David Choc**

---

© 2025 VitalSpace
