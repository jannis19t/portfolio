# Jannis — osobní portfolio

Jednostránkové osobní portfolio webového vývojáře. Web představuje autora, jeho
dovednosti a ukázkové projekty v moderním, responzivním rozhraní s tmavým
barevným motivem.

## Náhled

Portfolio obsahuje tyto části:

- úvodní sekci s krátkým představením a výzvou k prohlédnutí projektů,
- informace o autorovi a statistiky,
- přehled používaných technologií,
- ukázkové projekty **Focus**, **Daily** a **Wander**,
- kontaktní sekci s e-mailovým odkazem,
- odkazy na GitHub a HTML/CSS validátory.

## Použité technologie

- HTML5
- CSS3
- responzivní layout pomocí Flexboxu a CSS Gridu
- CSS animace a plynulé scrollování
- Google Fonts — [Manrope](https://fonts.google.com/specimen/Manrope) a
  [DM Mono](https://fonts.google.com/specimen/DM+Mono)
- SVG favicon

Projekt nevyžaduje JavaScript, bundler ani další závislosti.

## Spuštění

Protože jde o statickou stránku, stačí otevřít soubor `index.html` v prohlížeči.
Pro pohodlnější vývoj lze použít libovolný lokální server, například:

```bash
npx serve .
```

Poté otevři adresu, kterou server vypíše do terminálu.

## Struktura projektu

```text
portfolio/
├── index.html   # Obsah a struktura celé stránky
├── style.css    # Vzhled, layout, responzivita a animace
├── favicon.svg  # Ikona stránky
└── README.md    # Dokumentace projektu
```

## Úpravy obsahu

Nejdůležitější odkazy a údaje jsou přímo v `index.html`:

- GitHub odkazy nahraď skutečnou adresou profilu nebo jednotlivých repozitářů.
- Adresu `ahoj@example.com` v kontaktní sekci nahraď vlastním e-mailem.
- Názvy, popisy a statistiky projektů uprav podle aktuálního portfolia.
- Rok v patičce aktualizuj podle potřeby.

Barevné proměnné a většinu vzhledu lze upravit na začátku souboru
`style.css` v sekci `:root`.

## Nasazení

Stránku lze bez úprav nasadit na libovolný hosting statických webů, například:

- GitHub Pages,
- Netlify,
- Vercel,
- Cloudflare Pages.

Při nasazení stačí publikovat obsah tohoto adresáře. Nejdůležitější je, aby
`index.html` zůstal v kořenu publikovaného projektu.

## Licence

Projekt slouží jako osobní portfolio. Obsah a grafické zpracování jsou určeny
pro tento web; před použitím v jiném projektu si ověř práva k jednotlivým
materiálům a fontům.