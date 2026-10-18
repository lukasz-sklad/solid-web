# SolidCraft Web — solid.lmk.one

Wydanie webowe [SolidCraft](https://github.com/tangency-labs/solidcraft) — parametrycznego modelowania 3D CAD w Rust i WebAssembly.

## Funkcje wydania webowego:
- **Akceleracja GPU:** WebGPU z automatycznym fallbackiem do WebGL2
- **Obsługa motywów:** Automatyczny motyw ciemny / jasny przez parametr URL (`?theme=light` / `?theme=dark`) oraz komunikaty `postMessage`
- **Wersja językowa:** Język polski (`pl`) i 14 innych języków
- **Otwieranie plików z URL:** Możliwość ładowania modeli 3D przez parametr `?url=` lub `?file=` (np. `?url=ceownik_druk3d_10cm.stl`)
- **Przykładowy model:** `ceownik_druk3d_10cm.stl` — profil ceownika do druku 3D (długość 10 cm)
