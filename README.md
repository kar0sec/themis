# Themis

**ISMS-Policy-Management nach BSI IT-Grundschutz**

Git-basiertes Informationssicherheits-Managementsystem – versioniert, reviewt,
automatisiert gebuildet und compliance-geprüft durch Probo.

## Prinzipien

- **Docs as Code** – Richtlinien, Verfahren und Konzepte in Markdown
- **Baustein-orientiert** – Ableitung aus BSI IT-Grundschutz (109 Bausteine)
- **Versioniert** – Git-History als auditierbarer Nachweis
- **PR-basiert** – Änderungen durchlaufen Governance-Gate (ISB → GF)
- **Automatisiert** – CI/CD mit Validierung, Preview und Dashboard-Deployment

## Struktur

| Verzeichnis | Inhalt |
|---|---|
| `bausteine-katalog.yml` | 109 BSI-Bausteine, 1.787 Anforderungen |
| `docs/policies/` | Sicherheitsrichtlinien (POL-*) |
| `docs/procedures/` | Verfahrensanweisungen (PROC-*) |
| `docs/concepts/` | Sicherheitskonzepte (CON-*) |
| `docs/evidence/` | Nachweise und Aufzeichnungen |
| `docs/risks/` | Risikoregister |
| `docs/templates/` | Vorlagen |
| `status/` | Status-Metriken (SSoT) |
| `scripts/` | Automatisierungsskripte |
| `.github/workflows/` | CI/CD-Pipelines |

## Workflow
