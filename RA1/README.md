# RA1 · Administració de serveis de directori, recursos i emmagatzematge

Material de teoria actualitzat al curs 2026-27 (Windows Server 2025 i clients Windows 11), amb ordres de PowerShell, `cmd` i Linux, pràctiques guiades i preguntes de repàs.

| # | Tema | Continguts |
|---|---|---|
| 1 | [Usuaris, grups i unitats organitzatives](01-usuaris-grups-ad/README.md) | Objectes d'AD, UO, tipus i àmbits de grup, AGDLP, SID i Paperera d'AD, altes massives amb CSV |
| 2 | [Perfils mòbils i redirecció de carpetes](02-perfils-mobils/README.md) | Tipus de perfil, perfil mòbil, carpeta particular, redirecció per GPO, resolució de problemes |
| 3 | [Permisos NTFS](03-permisos-ntfs/README.md) | ACL i ACE, permisos estàndard i especials, herència, regles, propietari, `icacls` |
| 4 | [Compartir carpetes a la xarxa (SMB)](04-comparticio-smb/README.md) | SMB 3.1.1, permisos de compartició, combinació amb NTFS, ABE, seguretat SMB 2024-2026 |
| 5 | [Directives de grup (GPO)](05-directives-gpo/README.md) | LSDOU, conflictes, directives i preferències, filtratge, `gpupdate` i `gpresult` |
| 6 | [Servidor d'impressió i desplegament per GPO](06-servidor-impressio/README.md) | Rol d'impressió, controladors, PrintNightmare, permisos, desplegament per GPO |
| 7 | [RAID i emmagatzematge en xarxa](07-raid-emmagatzematge/README.md) | RAID 0/1/5/6/10, Espacios de almacenamiento, `mdadm`, ZFS, NAS, SAN, iSCSI |
| 8 | [Alta disponibilitat i continuïtat del negoci](08-alta-disponibilitat/README.md) | RPO/RTO, CPD secundari, rèpliques, clústers, regla 3-2-1-1-0, pla de contingència |

## Notes

- Les imatges dels diàlegs de Windows són **recreacions esquemàtiques** amb la interfície en castellà. Els números taronja coincideixen amb els passos del text.
- Els diagrames de flux estan fets amb Mermaid i GitHub els mostra directament.
- Les respostes de les preguntes de repàs estan amagades: clica **Respostes** per veure-les.
