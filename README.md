# Globe

An independent, reusable 3D globe. It belongs to no project — other projects copy from here.

- `index.html` — the whole thing, one file, no build step. Country fills, crisp vector borders,
  tiered labels (16 major countries always visible → all 177 on zoom; 62 major cities in two tiers).
  Includes the dateline-unwrap fill fix and the polar-cap fix (v4).
- Loads three.js, topojson-client and the world-atlas map from the jsDelivr CDN. No data layers.
- Live: https://ian-sanghyuk-han.github.io/globe/

## Lineage

Built inside Batavia Project · World Trading Live (`batavia-wtl`, `site/labs/globe-base.html` v4),
then used as the seed for After Flight and Estela. Set apart here on 2026-09-19 so the clean
base has its own home.

## Known issue

On some iPhones the page stays blank (the importmap + CDN module loader). Not fixed yet.

---

독립 지구본. 어느 프로젝트에도 속하지 않는 보존본입니다. 새 프로젝트는 이 `index.html`을 복사해서 시작합니다.
