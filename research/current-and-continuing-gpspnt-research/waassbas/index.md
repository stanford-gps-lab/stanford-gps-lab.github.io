---
layout: page
title: "Research"
permalink: /research/current-and-continuing-gpspnt-research/waassbas/
---

<div class="research-layout">
  {% include research-sidebar.html %}

  <div class="research-content">

# WAAS / SBAS

<img src="{{ '/assets/img/research/waas-banner.jpg' | relative_url }}"
     alt="WAAS / SBAS"
     class="research-page-image">

## Overview

The Stanford GPS Laboratory has been a pioneer in the development of
Satellite-Based Augmentation Systems (SBAS) for civil aviation. SBAS
improves the accuracy, integrity, availability, and continuity of Global
Navigation Satellite Systems (GNSS), enabling aircraft to safely perform
precision approach and landing procedures.

The Wide Area Augmentation System (WAAS) is the United States'
implementation of SBAS. WAAS combines GPS satellites, a network of
precisely surveyed reference stations, master processing stations,
uplink facilities, and geostationary satellites to monitor satellite
ranging errors and broadcast real-time correction and integrity
information to users.

Researchers in the Stanford GPS Lab have played a leading role in the
algorithms, integrity monitoring techniques, and performance analyses
that underpin WAAS and other SBAS implementations worldwide.

---

## Research Topics

- Wide Area Differential GPS
- Satellite orbit and clock correction algorithms
- Integrity monitoring and protection levels
- Ionospheric delay estimation
- Availability analysis
- Multi-frequency and multi-constellation SBAS
- Next-generation DFMC SBAS

---

## Stanford GPS Lab Contributions

The laboratory has contributed to many aspects of WAAS research,
including:

- Integrity algorithms for aviation navigation
- Ionospheric threat modeling
- Protection level computation
- Availability optimization
- Dual-frequency SBAS development
- International SBAS interoperability

---

## Related Research

- GBAS / LAAS
- RAIM / ARAIM
- Multi-Constellation GNSS
- Integrity Monitoring
- Precision Aircraft Landing

---

## Selected Publications

*Publications related to WAAS will be listed here.*

```
{% assign pubs = site.publications | where_exp:"item","item.tags contains 'WAAS'" %}
```

(or whatever publication organization you decide to use later.)

---

## Additional Resources

* Add presentations
* Research reports
* Videos
* Historical photographs

  </div>
</div>
