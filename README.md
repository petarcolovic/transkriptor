# Transkriptor

Program za automatsku transkripciju audio i video snimaka (intervjua, fokus grupa,
predavanja) pomoću Whisper modela za prepoznavanje govora. Sve se obrađuje na Vašem
računaru: snimci se nigde ne šalju, što je važno kada radite sa podacima učesnika
istraživanja.

Radi na Windows 10 i 11 (64-bit).

## Preuzimanje

- **[Transkriptor_Windows.zip](../../releases/download/v1.0/Transkriptor_1.0_Windows.zip)**
  — sam program, obavezno (oko 300–400 MB)
- [Transkriptor_GPU_dodatak.zip](../../releases/download/v1.0/Transkriptor_1.0_Windows_GPU_dodatak.zip)
  — opciono, samo za računare sa NVIDIA grafičkom karticom (oko 1,3 GB)
- [UPUTSTVO_ZA_STUDENTE.txt](../../releases/download/v1.0/UPUTSTVO_ZA_STUDENTE.txt)
  — detaljno uputstvo (nalazi se i u ZIP-u sa programom)

Linkovi uvek vode do najnovije verzije. Sve verzije su na stranici
[Releases](../../releases). Na toj stranici ne preuzimajte stavke „Source code” —
to nije program.

## Ukratko

1. Raspakujte `Transkriptor_Windows.zip` (desni klik → „Izdvoji sve…” / „Extract All…”).
2. U folderu `Transkriptor` pokrenite `Transkriptor.exe`. Ako Windows prikaže poruku
   „Windows je zaštitio računar”, kliknite „Više informacija” → „Ipak pokreni”.
3. Dodajte snimke, izaberite jezik i kliknite „Pokreni transkripciju”. Pri prvom
   korišćenju model se jednom preuzima sa interneta; posle toga program radi i bez njega.

Postavljanje GPU dodatka je opisano korak po korak u uputstvu (odeljak 5).

## Važno

Automatska transkripcija nije savršena. Transkript uvek proverite slušajući snimak,
posebno imena i stručne termine. Program ne razlikuje govornike.
