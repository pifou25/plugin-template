# Template de plugin pour Jeedom

[![semantic-release: angular](https://img.shields.io/badge/semantic--release-angular-e10079?logo=semantic-release)](https://github.com/semantic-release/semantic-release)
[![Build Master](https://github.com/pifou25/plugin-template/actions/workflows/semantic-release.yml/badge.svg?branch=master)](https://github.com/pifou25/plugin-template/actions/workflows/semantic-release.yml)
![GitHub release (with filter)](https://img.shields.io/github/v/release/pifou25/plugin-template)

Validation PHP Version (branche BETA) :

![PHP 7.3](https://github.com/jeedom/plugin-template/actions/workflows/lint_Php73.yml/badge.svg?branch=beta)
![PHP 7.4](https://github.com/jeedom/plugin-template/actions/workflows/lint_Php74.yml/badge.svg?branch=beta)

Validation Code int (branche BETA):

![PHP](https://github.com/jeedom/plugin-template/actions/workflows/php.yml/badge.svg?branch=beta)
![PHP](https://github.com/jeedom/plugin-template/actions/workflows/codeLintGlobal.yml/badge.svg?branch=beta)


--------
Validation PHP Version (branche MASTER) :

![PHP 7.3](https://github.com/jeedom/plugin-template/actions/workflows/lint_Php73.yml/badge.svg?branch=master)
![PHP 7.4](https://github.com/jeedom/plugin-template/actions/workflows/lint_Php74.yml/badge.svg?branch=master)

Validation Code int (branche MASTER):

![PHP](https://github.com/jeedom/plugin-template/actions/workflows/php.yml/badge.svg?branch=master)
![PHP](https://github.com/jeedom/plugin-template/actions/workflows/codeLintGlobal.yml/badge.svg?branch=master)

Ce "template de plugin" sert de base à la réalisation de plugins pour **Jeedom**.

La documentation générale relative à la conception de plugin est consultable [ici](https://doc.jeedom.com/fr_FR/dev/). Dans le détail :   
* [Utilisation du template de plugin](https://doc.jeedom.com/fr_FR/dev/plugin_template) : Le template de plugin est une base de plugin pour Jeedom qui doit être adaptée avec l'id de votre plugin et à laquelle il suffit d'ajouter vos propres fonctions. 
* [Fichier info.json](https://doc.jeedom.com/fr_FR/dev/structure_info_json) : Intégré depuis la version 3.0 de Jeedom, le fichier **info.json** est obligatoire pour le bon fonctionnement des plugins et leur bon déploiement sur le Market Jeedom.
* [Icône du plugin](https://doc.jeedom.com/fr_FR/dev/Icone_de_plugin) : Afin de pouvoir être publié sur le Market Jeedom, tout plugin doit disposer d’une icône. Attention à ne pas utiliser le même code couleur que les icônes des plugins Jeedom officiels.
* [Widget du plugin](https://doc.jeedom.com/fr_FR/dev/widget_plugin) : Présentation des différentes manières d'inclure des widgets personnalisés au plugin.
* [Documentation du plugin](https://doc.jeedom.com/fr_FR/dev/documentation_plugin) : Présentation de la mise en place d'une documentation car un bon plugin n'est rien sans documentation adéquate.
* [Publication du plugin](https://doc.jeedom.com/fr_FR/dev/publication_plugin) : Description des pré-requis indispensables à la publication du plugin.

---
Si vous créez une branch nommée prettier, le robot workflows fera une passe complete sur le code pour que le code soit le plus uniforme possible.

### Semantic Release

Ce projet suit la convention [Semantic Release](https://semantic-release.gitbook.io/semantic-release/) pour les messages de commit. 
Ceci afin de générer automatiquement le changelog et les packages. Le ChangeLog
 doit être dans docs/fr_FR/changelog.md (et docs/fr_FR/changelog_beta.md pour
  la branche beta) ; et le numéro de version du plig

feat: test pour release 1.3.0