# 🏷 Metadata Tag & Property Taxonomy

> This file defines the tags, properties, and custom fields used in scene headers and character files across the Dani & Cris vault.

---

## 🧾 Tags

### POV
| Tag | Meaning |
|-----|---------|
| #pov/dani | Dani’s point of view |
| #pov/cris | Cris’s point of view |
| #pov/mateo | Mateo’s point of view |

### Arc
| Tag | Meaning |
|-----|---------|
| #arc/dani | Dani’s emotional arc |
| #arc/cris | Cris’s emotional arc |
| #arc/mateo | Mateo’s arc of manipulation and loss |

### Scene Setting
| Tag | Location |
|------|----------|
| #scene/porch | Porch swing scenes |
| #scene/bedroom | Private bedroom scenes |
| #scene/livingroom | Open domestic space (non-bedroom) |

### Themes
| Tag | Meaning |
|------|---------|
| #theme/erosion | Slow loss of control or identity |
| #theme/reckoning | Emotional confrontation and clarity |
| #theme/control | Intentional manipulation or dominance |
| #theme/structure | Obedience, rules, systems introduced |

### Emotional Tone
| Tag | Usage |
|------|-------|
| #emotion/crack | Moment of emotional fracture |
| #emotion/threshold | On the edge of surrender or action |
| #emotion/devastation | Full collapse |
| #emotion/recovery | Reclaiming self or relationship |

### Status
| Tag | Purpose |
|------|--------|
| #draft | Scene is in progress |
| #done | Final or polished scene |
| #needswork | Needs revision or expansion |

---

## 🧾 Frontmatter Properties

| Property | Description | Required? |
|----------|-------------|-----------|
| title | Scene title (as displayed) | ✅ Yes |
| scene_id | Unique scene number (e.g. `03`) | Optional |
| date | Date created or last revised | Optional |
| status | Progress tag (e.g. `#draft`) | ✅ Yes |
| pov | POV tag (e.g. `#pov/cris`) | ✅ Yes |
| arc | One or more arc tags | Optional |
| setting | Physical scene location | Optional |
| theme | Thematic filter (optional) | Optional |
| emotion | Core emotional tone | Optional |
| linked_arcs | `[[Links]]` to Arc files | Optional |
| related_rules | `[[Links]]` to rule notes | Optional |

---

## 📚 Notes

- Tags begin with `#`, while properties can be either plain text or tag-form
- Frontmatter (`---`) must be at the very top of the note
- Obsidian’s **Properties editor** reads these fields and will prompt for clean entries
