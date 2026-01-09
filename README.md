# AboBuddy – Subscription Categories Catalog (JSON)

Dieses Repository stellt einen **öffentlich erreichbaren Kategorien-Katalog** als **JSON** bereit, damit AboBuddy die Kategorien **aus einer externen Quelle** laden kann (Kurs-Anforderung: *external data fetch + JSON processing*).

## Inhalt

- `docs/categories.json` – Hauptkatalog (offizielle Kategorien)
- optional: `README.md` – diese Doku


## JSON-Schema

`categories.json` ist ein Array von Objekten:

```json
[
  {
    "category_id": "streaming_video",
    "category_name": "Streaming (Video)",
    "category_color_hex": "#FF6825"
  }
]
