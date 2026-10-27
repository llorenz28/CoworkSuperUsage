# Release manifest — v1.0.0

All hashes use SHA-256. Binary artifacts are published byte-for-byte from the authoritative sources.

| Published file | Bytes | SHA-256 | Role | Privacy/access note |
|---|---:|---|---|---|
| `CoworkSuperUsage.pbix` | 1,023,505 | `3B8B009022B39D6B3D0A87559D3C8708C6E6EE1D7A7BBD06E3EF98FDE6357530` | Ready-to-use report | Package scan found no local path strings; public download |
| `CoworkSuperUsage.pbit` | 544,510 | `C25CAAF4490F4EBC10065CE1659D2DC8A3FE4E761234534A7CD5A0A1BB03C036` | Reusable template | Package scan found no local path strings; public download |
| `CoworkSuperUsage-Interpretation-Guide.pptx` | 3,580,368 | `93058C53F522EC2BB385EEAA4D948CEE32D7493AA8A13C15B5FD2A6A3C554E75` | 15-slide interpretation guide | Existing package sensitivity-label metadata retained unchanged |
| `media/CoworkSuperUsage-Walkthrough.mp4` | 55,589,491 | `D7C61347C958AC5452FD27D3D6B87DFC80151F06E90F15F23D38F2CE34425AB7` | Natural neural-voice, tight-transition walkthrough | 1920×1080; ~3:43; public download |
| `sample-data/CoworkWeeklyMetrics.csv` | 1,117,045 | `DB9198F59E8F29E7CDAD1C7BC5DC301FDA1110A7672FAC0B04136F91CF38CB39` | Synthetic usage facts | 14,599 synthetic rows; no email addresses or local paths |
| `sample-data/PeopleMetaData.csv` | 9,969 | `41581DE7C276C8A36F65913ACF5B65B5CEF164A538BED25AAB7275EB391D17BB` | Synthetic dimension data | 240 synthetic rows; no personal names or email addresses |

Validation confirmed all fact-table IDs match `SYN-P####` / `SYN-H####`, all metadata IDs match `SYN-H####`, and there are no orphan metadata joins.
