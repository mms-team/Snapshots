# Nolus - nolus-rila

## Snapshot:
https://share.mms.team/nolus/nolus-rila/

 How to apply snapshot

``sudo systemctl stop nolusd``

``nolusd tendermint unsafe-reset-all --home $HOME/.nolus --keep-addr-book``

``wget https://share.mms.team/nolus/nolus-rila/snap_nolus.tar.gz``

``tar -xzvf snap_nolus.tar.gz``

``rm snap_nolus.tar.gz``

``sudo systemctl restart nolusd && sudo journalctl -fu nolusd -o cat``
