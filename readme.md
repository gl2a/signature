# Signatures e-mail GL2A (HTML)

Ce dépôt contient des signatures e-mail au format HTML prêtes à être copiées/collées dans Gmail / Outlook.

## Contenu

- **Signature logo uniquement** : template avec le logo GL2A (carré)
- **Signature avec photo** : template avec photo de profil + logo (format compact)

---

## 1 - Personnaliser les variables

Dans les templates HTML, remplace les valeurs suivantes avec CTRL + F pour éviter les oublis :

### Variables à remplacer
- `FIRST_NAME` → votre prénom  
- `LAST_NAME` → votre nom  
- `PHONE` → votre numéro affiché (ex: `+33 1 23 45 67 89`)
- `MY_PHOTO` → le nom de votre fichier photo (ex: `jean.jpg`)

> Astuce : gardez une convention de nom de fichier simple en minuscules, sans accents, sans espaces :  
> `prenom.jpg`

---

## 2 - Ajouter / uploader votre photo de profil

### Emplacement
Ajoutez votre photo dans le dossier :

```
assets/profile/
```

### Nom du fichier
Exemple : `jean.jpg`

## 3 - IMPORTANT — Ne pas commit vos personnalisations dans les templates
Les signatures HTML présentes dans le dépôt sont des templates.
Les modifications personnelles (nom, téléphone, photo, etc.) ne doivent pas être commitées.
