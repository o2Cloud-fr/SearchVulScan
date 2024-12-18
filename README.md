# SearchVulScan

**SearchVulScan** est une application Windows qui permet de rechercher facilement des logiciels installés sur un système à partir d'un fichier CSV contenant des informations sur les logiciels installés.

L'application fournit une interface graphique simple avec une barre de recherche et une liste des résultats correspondant à la recherche.

---

## Fonctionnalités

- **Recherche de logiciels** : Recherchez des logiciels installés par leur nom ou version à l'aide d'une barre de recherche.
- **Affichage des résultats** : Affiche les résultats de la recherche dans une `ListBox` avec le nom et la version du logiciel.
- **Gestion d'un fichier CSV** : Charge un fichier CSV contenant les informations des logiciels installés et les affiche dans l'application.
- **Interface graphique intuitive** : Permet d'effectuer des recherches de manière fluide et simple.

---

## Exemple d'utilisation

1. Lancer l'application `SearchVulScan`.
2. La fenêtre principale vous permettra de saisir des termes de recherche dans une barre de texte.
3. À mesure que vous tapez, les résultats s'affichent dynamiquement dans la liste en dessous.
4. Le fichier CSV contenant les informations des logiciels installés est situé sur le bureau de l'utilisateur, sous le nom `installed_software.csv`.

---

## Fonctionnement

L'application charge un fichier CSV situé sur le bureau de l'utilisateur (`installed_software.csv`). Chaque ligne du fichier CSV contient des informations sur un logiciel installé : le nom, la version et la date d'installation.

Lorsque vous tapez un terme dans la barre de recherche, l'application filtre les logiciels en fonction du nom du logiciel et affiche les résultats correspondants dans la liste déroulante.

---

## Pré-requis

- Windows 10 ou supérieur
- .NET Framework 4.8.1 ou supérieur

## 🎯 Utilisation

1. **Recherche** : Tapez le nom du logiciel que vous souhaitez rechercher dans le champ de texte situé en haut de l'interface.
2. **Affichage des résultats** : Les résultats de la recherche s'affichent dans une `ListBox` en dessous du champ de recherche.

---

## Installation

1. Clonez ce dépôt sur votre machine locale :

   ```bash
   git clone https://github.com/o2Cloud-fr/SearchVulScan.git

## Authors

- [@MyAlien](https://www.github.com/MyAlien)
- [@o2Cloud](https://www.github.com/o2Cloud-fr )

## Badges

Add badges from somewhere like: [shields.io](https://shields.io/)

[![MIT License](https://img.shields.io/badge/License-o2Cloud-yellow.svg)]()


## Contributing

Contributions are always welcome!

See `contributing.md` for ways to get started.

Please adhere to this project's `code of conduct`.


## Feedback

If you have any feedback, please reach out to us at github@o2cloud.fr


## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://vcard.o2cloud.fr/)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/remi-simier-2b30142a1/)


## 🛠 Skills
C#


## License

[Apache-2.0 license](https://github.com/o2Cloud-fr/SearchVulScan/blob/main/LICENSE)


![Logo](https://o2cloud.fr/logo/o2Cloud.png)


## Related

Here are some related projects

[Awesome README](https://github.com/o2Cloud-fr/SearchVulScan/blob/main/README.md)


## Roadmap

- Additional browser support

- Add more integrations


## Support

For support, email github@o2cloud.fr or join our Slack channel.


## Tech Stack

## Used By

This project is used by the following companies:

- o2Cloud
- MyAlienTech

