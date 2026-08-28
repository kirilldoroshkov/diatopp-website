# DIATOPP staging

Target URL: https://diatopp.ee/dev/

Purpose: isolated review area for DIATOPP website changes before production.

Planned workflow:
- production site remains at https://diatopp.ee/
- staging copy lives under /dev/
- changes are reviewed on /dev/ first
- approved changes are then promoted to production

Current blocker: Zone FTPS authentication must be restored before the live WordPress files/database can be copied into /dev/.
