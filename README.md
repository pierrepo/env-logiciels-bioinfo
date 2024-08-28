# Environnements logiciel pour la bioinformatique

## Compilation du cours avec conda

Créer l'environnement conda :

```bash
conda env create -f environment.yml
```

Charger l'environnement conda :

```bash
conda activate env-logiciel-bioinfo
```

Compiler le cours :

```bash
jupyter-book build cours
```

La version HTML du cours se trouve dans le répertoire `cours/_build/html`.

