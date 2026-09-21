# Business Model Canvas — Kulturfaden

> **Kulturfaden — Der rote Faden hinter der Kultur.**
>
> Ein kuratiertes Verzeichnis für Termine, Gespräche, Netzwerke,
> Entscheidungen und Entwicklungen rund um Kultur.

---

## 1. Business Model Canvas

```mermaid
flowchart TB

    KP["🔑 Schlüsselpartner<br/><br/>
    • Kulturorganisationen<br/>
    • Verbände & Netzwerke<br/>
    • Stadt & öffentliche Institutionen<br/>
    • Kulturpolitische Akteure<br/>
    • Kulturregionen<br/>
    • Fachverbände<br/>
    • Veranstalter<br/>
    • perspektivisch: Daten-/Technologiepartner"]

    KA["🔧 Schlüsselaktivitäten<br/><br/>
    • Quellen recherchieren<br/>
    • Veranstaltungen erfassen<br/>
    • Relevanz prüfen<br/>
    • Daten kuratieren<br/>
    • Quellen beobachten<br/>
    • Daten aktualisieren<br/>
    • Beziehungen zwischen Terminen herstellen<br/>
    • Plattform entwickeln"]

    KR["🧩 Schlüsselressourcen<br/><br/>
    • Veranstaltungsdaten<br/>
    • Quellenverzeichnis<br/>
    • redaktionelles Wissen<br/>
    • Taxonomie / Themenmodell<br/>
    • Software & Infrastruktur<br/>
    • Marke Kulturfaden<br/>
    • Community / Netzwerk<br/>
    • langfristig: historischer Datenbestand"]

    VP["💡 Wertangebote<br/><br/>
    • Orientierung im kulturellen Ökosystem<br/>
    • Ein Kalender für die Prozesse hinter der Kultur<br/>
    • Zentrale Übersicht fragmentierter Informationen<br/>
    • Auffindbarkeit kulturpolitischer Termine<br/>
    • Zugang zu Netzwerken & Fachdiskursen<br/>
    • Verbindung von Terminen, Themen und Organisationen<br/>
    • Recherche- und Monitoringwerkzeug<br/>
    • Einstieg zu den Originalquellen"]

    CR["🤝 Kundenbeziehungen<br/><br/>
    • Selbstbedienung<br/>
    • niedrigschwelliger Zugang<br/>
    • Vertrauen durch Quellenangaben<br/>
    • redaktionelle Transparenz<br/>
    • perspektivisch Newsletter<br/>
    • perspektivisch personalisierte Beobachtung"]

    CH["📡 Kanäle<br/><br/>
    • kulturfaden.de<br/>
    • Suchmaschinen<br/>
    • Newsletter<br/>
    • Social Media<br/>
    • Kulturorganisationen<br/>
    • Partnernetzwerke<br/>
    • Verlinkungen von Originalquellen<br/>
    • Mundpropaganda"]

    CS["👥 Zielgruppen<br/><br/>
    • freie Kulturszene<br/>
    • Kulturmanager:innen<br/>
    • Kulturinstitutionen<br/>
    • Kulturpolitisch Interessierte<br/>
    • Kulturpolitiker:innen<br/>
    • Verwaltung<br/>
    • Journalist:innen<br/>
    • Wissenschaft / Forschung<br/>
    • Kulturförderung<br/>
    • Studierende / Nachwuchs"]

    COST["💸 Kostenstruktur<br/><br/>
    • Entwicklung<br/>
    • Hosting / Infrastruktur<br/>
    • Domain<br/>
    • Datenpflege<br/>
    • redaktionelle Arbeit<br/>
    • Recherche<br/>
    • Monitoring / Automatisierung<br/>
    • Wartung<br/>
    • ggf. externe Datenquellen"]

    REV["💰 Einnahmequellen<br/><br/>
    Zunächst:<br/>
    • keine bzw. minimale Monetarisierung<br/><br/>
    Perspektivisch:<br/>
    • Fördermittel<br/>
    • institutionelle Partnerschaften<br/>
    • Sponsoring<br/>
    • Fördermitgliedschaft<br/>
    • Premium-Dienste für Monitoring / Daten<br/>
    • API / Datennutzung<br/>
    • Auftragsdaten / Research"]

    KP --> KA
    KA --> VP
    KR --> VP

    VP --> CR
    VP --> CS
    VP --> CH

    KA --> COST
    KR --> COST
    CR --> REV
    CS --> REV

    style VP stroke-width:4px
