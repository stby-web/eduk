# EduVerse MAX

Hotová statická web stránka pre základné školy.

## Ako spustiť

Stačí otvoriť `index.html` v prehliadači.

Demo účty:

- učiteľ: `ucitel` / `1234`
- žiak: `ziak` / `1234`

## Ako dať na GitHub Pages

1. Vytvor nový GitHub repozitár.
2. Nahraj doň tieto súbory:
   - `index.html`
   - `.nojekyll`
   - `README.md`
3. Choď do `Settings → Pages`.
4. Nastav:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
5. Ulož.

Stránka bude na adrese:

`https://TVOJE-MENO.github.io/NAZOV-REPO/`

## Dôležité

Táto verzia je bez backendu. Dáta sa ukladajú cez `localStorage`, čiže ostávajú iba v konkrétnom prehliadači.
Pre reálnu školskú aplikáciu treba Supabase/Firebase backend.
