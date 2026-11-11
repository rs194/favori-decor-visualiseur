# Modèle de détection des façades — visualiseur FAVORI DÉCOR

Fichiers publics utilisés par l'outil « Vos façades sur votre photo » du visualiseur du site FAVORI DÉCOR.
L'outil fonctionne entièrement dans le navigateur du visiteur : la photo n'est jamais envoyée. Seuls ces fichiers,
identiques pour tous les visiteurs, sont téléchargés (via jsDelivr), puis vérifiés par leur empreinte SHA-256 avant
usage.

| Fichier | Octets | SHA-256 |
| --- | --- | --- |
| `mobilesam-encoder-fp16.0d691f8e244a.onnx` | 14 178 093 | `0d691f8e244a919c8a90d267d9b98e187cb1e1ca79a3c865634791869e59f56d` |
| `mobilesam-decoder-fp16.3f0c3fd8fc37.onnx` | 8 386 707 | `3f0c3fd8fc37c19c346ed35a37e2f27bbbf84f9728d238e9f3ce457364a37184` |

Origine, auteurs, modifications et licences (Apache 2.0 pour MobileSAM, MIT pour TinyViT) : `LICENCE-MobileSAM.txt`.
Ce dépôt ne contient aucun code ni aucune donnée du site. Ne pas modifier un fichier existant : un nouveau modèle
reçoit un nouveau nom (empreinte dans le nom).

---

Public files used by the “Your fronts on your own photo” tool of the FAVORI DÉCOR website visualiser. The tool runs
entirely in the visitor's browser: the photo is never uploaded. Licences: see `LICENCE-MobileSAM.txt`
(MobileSAM: Apache 2.0; TinyViT: MIT).
