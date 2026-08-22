# ymauray/scoop-bucket

[![Validation des manifests](https://github.com/ymauray/scoop-bucket/actions/workflows/validate-manifests.yml/badge.svg)](https://github.com/ymauray/scoop-bucket/actions/workflows/validate-manifests.yml)
[![Licence MIT](https://img.shields.io/badge/Licence-MIT-yellow.svg)](LICENSE)

Bucket Scoop pour les outils en ligne de commande maintenus par [@ymauray](https://github.com/ymauray).

## Installer le bucket

```powershell
scoop bucket add ymauray https://github.com/ymauray/scoop-bucket
```

Installez ensuite un outil :

```powershell
scoop install ymauray/epubst
```

## Manifests disponibles

- `epubst`
- `excelst`
- `johannes`
- `paige`
- `scrubx`

## Mises à jour des manifests

Les manifests sont mis à jour automatiquement par les workflows de publication des dépôts sources. Les pull requests manuelles de mise à jour ne sont pas acceptées, car elles seraient écrasées lors de la prochaine publication.

## Validation

GitHub Actions valide la structure JSON de chaque manifest puis l'installe avec Scoop sur Windows.
