# Intrams attendance

Static attendance frontend hosted on GitHub Pages.

Student records, photo evidence and access-code hashes are stored in a separate private Google backend. This repository contains no real student roster, photos, administrator code or representative codes. Fictional demonstration records are labeled in the interface.

Open the published website and enter the private code assigned by the event administrator. The backend URL is public configuration; every data request still requires a valid access code. Camera and location access require HTTPS and browser permission.

Administrators manage section representatives and one all-section attendance assistant in Event setup. Both sessions must be approved to count a full day. The browser keeps the access code in tab memory only.

Deploy from the main branch root using GitHub Pages. All website assets use relative paths so project-site hosting works.
