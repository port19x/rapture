# Rapture

Currently hosts a gitea instance mirroring my repos as well as a copy of my website and a grafana dashboard

![2023-09-18_12-48](https://github.com/port19x/rapture/assets/82055622/bf43d6f9-e225-448b-833a-8323e7757803)

## Roadmap

[*blog post*](https://port19.xyz/tech/status-update-2309/)

- [ ] Make this the primary host of my website
- [ ] Improve security posture
  - [ ] SSH Fingerprint in Playbook
  - [ ] Resource limits in docker compose
  - [ ] Non-root user
  - [x] Formalized state backup strategy - `scp -r root@hsnipe.moe:/mnt/ ./backup`
- [ ] Host PoC [Django](https://docs.djangoproject.com/en/2.2/howto/deployment/) webapp
- [ ] Host [Jitsi](https://github.com/jitsi/docker-jitsi-meet) Instance
- [x] Host [Kavita](https://github.com/Kareadita/Kavita) eBook Library
- [ ] Migrate to [netcup](https://www.netcup.de/bestellen/produkt.php?produkt=2892)
- [ ] Host [Arch Linux Mirror](https://wiki.archlinux.org/title/DeveloperWiki:NewMirrors)

## Wall of Shame

- [Calibre Web](https://github.com/janeczku/calibre-web) - Want to host some ebooks? How about you generate a database first?
- [Syncplay](https://github.com/Syncplay/syncplay/issues/573#issuecomment-1362880943) - Want to do SSL Termination on the reverse proxy? No way!
