# Foreldreportal

Testutkast for en informasjonsportal/webapp for Roterud G2014.

## Hva finnes her?

- `index.html` – klikkbar testside med løsningsforslag, eksempelkalender, kampkort, realiseringsplan og GitHub Pages-instruksjoner.
- `kalender.html` – egen kalenderside der brukeren kan velge mellom ukeplan og månedskalender.
- `styles.css` – responsivt design for mobil, nettbrett og desktop.
- `.github/workflows/pages.yml` – GitHub Actions-oppsett for publisering til GitHub Pages ved push til `work` eller `main`.

## Vise som delbar testside med GitHub Pages

1. Push endringene til GitHub.
2. Gå til repositoryets **Settings → Pages**.
3. Velg **GitHub Actions** som kilde.
4. Workflowen `Publish test site` publiserer automatisk ved push til `work` eller `main`.
5. GitHub viser deretter en delbar test-URL i Pages-innstillingene og i workflow-runnen.

## Videre realisering

Første versjon kan være statisk og manuelt vedlikeholdt. Neste steg bør være å flytte aktivitetsdata til en enkel datakilde, for eksempel JSON, Google Sheets eller et lett CMS, før løsningen utvides til flere lag.
