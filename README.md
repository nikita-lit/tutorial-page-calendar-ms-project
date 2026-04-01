# MS Projecti Õpetusveeb

See projekt on loodud eesmärgiga pakkuda kasutajatele selget ja visuaalset juhist Microsoft Projecti (MS Project) kasutamiseks. Veebileht keskendub kolmele peamisele teemale: kalendrite loomine, arvutusväljade lisamine ja diagrammide genereerimine.

---

## Sisukord
1. [Projekti kirjeldus](#projekti-kirjeldus)
2. [Tehtud tööd](#tehtud-tööd)
3. [Kasutatud tehnoloogiad](#kasutatud-tehnoloogiad)
4. [Lehekülgede struktuur](#lehekülgede-struktuur)
5. [Visuaalid](#visuaalid)

---

## Projekti kirjeldus
Projekti raames valmis kaasaegse disainiga veebileht, mis on:
- **Responsiivne**: Toimib nii arvutis kui nutiseadmes.
- **Interaktiivne**: Sisaldab piltide suurendamise (lightbox) funktsiooni ja sujuvaid animatsioone.
- **Kasutajasõbralik**: Selge navigeerimine ja loogiline ülesehitus.

> [!NOTE]
> Veebileht on optimeeritud Microsoft Project 2021 [^1] versiooni baasil loodud juhendite kuvamiseks, kuid sammud on sarnased ka teiste versioonidega.

---

## Tehtud tööd

Allpool on toodud nimekiri projektis teostatud ülesannetest:

### Lõpetatud ülesanded
- [x] **MS Projecti õpetuslehe loomine**: Üldise raamistiku ja struktuuri paikasättimine.
- [x] **Uue kalendri loomise juhend**: `index.html` sisu koostamine.
- [x] **Arvutusvälja lisamise juhend**: `valem.html` sisu koostamine.
- [x] **Diagrammide loomise juhend**: `diagramm.html` sisu koostamine.
- [x] **Teksti genereerimine**: Sisu loomiseks on kasutatud AI abi (Gemini).
- [x] **Oma pildid**: Kõik ekraanitõmmised on teostatud MS Projecti tarkvaras.
- [x] **Navigeerimismenüü**: Ühtne ja funktsionaalne menüü kõikidel lehtedel.

> [!WARNING]
> Kui muudad faile käsitsi, veendu, et kõik pilditeed (images/) jääksid kehtivaks, muidu ei ilmu visuaalid lehel.

---

## Kasutatud tehnoloogiad
| Tehnoloogia | Kasutusvaldkond |
| :--- | :--- |
| **HTML5** | Veebilehe struktuur ja semantika |
| **CSS3** | Disain, animatsioonid ja *glassmorphism* efektid |
| **JavaScript** | Interaktiivsus (lightbox, scroll-animations) |
| **Font Awesome** | Ikoonide kuvamine |
| **Google Fonts** | Tüpograafia (modernsed fondid) |

---

## Lehekülgede struktuur
| Fail | Kirjeldus |
| :--- | :--- |
| `index.html` | Pealeht: Uue kalendri loomise sammud |
| `valem.html` | Arvutusväljade ja valemite seadistamine |
| `diagramm.html` | Diagrammide ja aruannete (reports) loomine |
| `style.css` | Ühtne stiilifail kogu projektile |

---

## Visuaalid
Siin on näide ühest veebilehe osast:

![MS Projecti kalendri seaded](images/3.png)

*Joonis 1: MS Projecti tööaja muutmise aken.*

---

## Koodi näide
Projekti kloonimiseks ja kohalikuks kasutamiseks kasuta järgnevat käsku:

```bash
git clone https://github.com/nikita-lit/tutorial-page-calendar-ms-project.git
```

---

## Lingid ja viited
- [GitHub Pages Docs](https://docs.github.com/en/pages)

> [!TIP]
> MS Projectis kalendrit luues veendu alati, et oled lisanud riiklikud pühad erandite (Exceptions) alla!

[^1]: MS Project 2021 on viimane versioon, mille põhjal ekraanitõmmised valmisid.
