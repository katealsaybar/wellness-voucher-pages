# Wellness Voucher pages (moved)

Since 30 Sep 2026 the Wellness Voucher landing page and its single terms page live on the dashboard domain:

- https://trk-salon-os.com/wellness-voucher/
- https://trk-salon-os.com/wellness-voucher/terms/

The real copy is in `katealsaybar/tararosesalon-dashboard-all` under `wellness-voucher/`. Edit it there.

Every page in this repo is now a redirect stub that carries the query string and hash across, so old links and UTM-tagged ads keep working. The Abu Dhabi and Dubai terms both point at the one terms page, and `404.html` sends any other path to the landing page. `assets/` stays in place in case anything still links to an image here.
