<!-- Format opisu jak w AGENTS.md (szablon wearefuture-ai/waf-sdlc). PR z Loop Factory przychodzi jako draft; merge robi człowiek. -->

## Co

<!-- Jedno, dwa zdania. "Fixes #123" zamyka issue po merge'u. -->

## Dlaczego

## Jak sprawdzone

- [ ] `bash .ai/validate.sh` zielone (komendy w `.ai/agentic.config.json`)
- [ ] testy dla zmienionego zachowania
- [ ] sprawdzone ręcznie, jeśli zmiana jest widoczna dla użytkownika: <!-- co i gdzie -->

## Ryzyka i co dalej

<!-- Co uruchamia się automatycznie po merge'u (wdrożenie, publikacja, migracja), co może się zepsuć, jak cofnąć, co zostaje na później. -->

## Przed merge'em

- [ ] etykiety: kategoria (`bug`, `feature`, `refactor`, `security`, `dependencies`, `documentation`); priorytet i ryzyko, jeśli nie średnie
- [ ] brak sekretów, tokenów i danych osobowych w zmianach
- [ ] nowe zależności uzasadnione w opisie
- [ ] review człowieka, także dla PR z Loop Factory
