# Avverkningsvakten Östergötland

Daily automatic screening of every felling notification (avverkningsanmälan) in
Östergötlands län, Sweden, against records of protected and red-listed species,
registered key habitats, modelled forest conservation value and the six-week
legal clock of 12 kap. 6 § miljöbalken. Built and refreshed every morning by
the project `260906_E_avverkning_watchdog` (R, open data only).

- `index.html`: the dashboard (open it, or view it on GitHub Pages)
- `today_list_latest.csv` / `.md`: today's ranked list of notifications that need a species survey
- `letters/`: draft letters (Swedish) for the top objects; drafts for a human to check and sign, nothing is sent

Sources: Skogsstyrelsen (Skogsdataportalen, open data), GBIF (DOI 10.15468/dl.5gbu2g,
CC BY-NC 4.0), SLU Artdatabanken (Rödlistan 2025, Dyntaxa, Artfakta), Naturvårdsverket
(NMD 2023, NVK Skog, Skyddad natur). Species records lag Artportalen by days to
weeks and exclude protected-class species; whether Skogsstyrelsen has acted on a
case must be confirmed from its dagboksblad. Licence of this repository's own
content: CC BY 4.0; the GBIF-derived species lists inherit CC BY-NC 4.0.
