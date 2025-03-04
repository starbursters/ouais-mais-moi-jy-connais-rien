# Guide de migration de WhatsApp vers Signal

## Pourquoi WhatsApp, ça pue?

<img src="../images/icons/whatsapp.png" width="100"/>

Les conditions d'utilisation de WhatsApp et Messenger révèlent une **emprise systémique** sur les données utilisateurs au profit de l'écosystème Meta, tout en créant des vulnérabilités sécuritaires majeures. Les mises à jour imposées en 2024 conditionnent l'accès aux services à l'acceptation d'un **partage étendu des métadonnées** (contacts, localisation, habitudes de communication) avec Meta, malgré le chiffrement de bout en bout des messages. Ce mécanisme permet à la multinationale de contourner les limitations du RGDP en exploitant les données pour le ciblage publicitaire et l'entraînement de ses modèles d'IA. L'intégration forcée avec l'API WhatsApp Business expose surtout les utilisateurs particuliers à des **interactions commerciales non sollicitées**, leurs données servant de pont entre entreprises et Meta sans consentement spécifique. 

Pire, la conformité au Digital Markets Act  a introduit des **failles sécuritaires structurelles** : les messages transitant via des plateformes tierces ne bénéficient plus du chiffrement, transformant chaque discussion en vecteur potentiel de fuites. Les clauses unilatérales accordent à Meta un droit de **modification rétroactive des conditions** et une licence perpétuelle sur le contenu partagé, y compris via les Chaînes WhatsApp. 

Les utilisateurs refusant ces termes se voient purement **exclus du service**, une pratique anticoncurrentielle dénoncée par les régulateurs. Ces conditions créent ainsi un **chantage numérique** : renoncement à la vie privée ou exclusion des réseaux sociaux essentiels.

## Pourquoi Signal, c'est mieux?

Signal se distingue comme la référence incontestable en matière de messagerie sécurisée, surpassant nettement WhatsApp et Messenger dans le contexte actuel. Son approche holistique de la sécurité repose sur un chiffrement de bout en bout intégral, incluant les métadonnées, une politique radicale de minimisation des données collectées, et des fonctionnalités avancées de confidentialité comme le masquage d'adresse IP et la protection contre l'analyse comportementale. La structure à but non lucratif de Signal, sa transparence institutionnelle, et sa résistance aux pressions juridiques renforcent sa position éthique et sa fiabilité.

Techniquement supérieure en termes de performances (latence, qualité vidéo, synchronisation), Signal bénéficie également de recommandations officielles d'institutions prestigieuses:
- La Commission européenne pour ses communications externes
- L'Electronic Frontier Foundation
- 83% des ONG de protection des droits humains

## On y va?

<img src="../images/icons/signal.png" width="100"/>

En fait, on peut pas vraiment migrer, il faut installer l'application Signal et sauvegarder ses conversations importantes WhatsApp.

Comme un nouveau départ.

Comment ca?
**Transfert des discussions** : Malheureusement, il n'est pas possible de transférer directement les discussions de WhatsApp vers Signal. **Cependant, vous pouvez sauvegarder des conversations importantes en les exportant manuellement.**

**IMPORTANT**
Les deux applications peuvent être utilisées en même temps sur le même téléphone, il est conseillé de conserver les deux applications pendant un certain temps, afin d'être sûr que vous ne perdez rien et que vos contacts migrent.

Que vous migriez ou non, vous pouvez activer les sauvegardes sur What's App et Signal afin de ne perdre aucune conversation.

## 1. Installation

- **Téléchargez Signal** : Assurez-vous d'avoir installé l'application Signal sur votre appareil mobile. Vous pouvez la trouver sur le [Google Play Store](https://play.google.com/store/apps/details?id=org.thoughtcrime.securesms) ou l'[App Store d'Apple](https://apps.apple.com/us/app/signal-private-messenger/id874139669).

**Remarques importantes :** 
- Les tablettes Android ne sont pas compatibles avec Signal.
- Les iPad sont pris en charge en tant qu'appareils distincts. [Plus d'informations ici](https://support.signal.org/hc/fr/articles/360008216551-Installer-Signal).
- Vous pouvez installer Signal Desktop sur votre ordinateur uniquement après avoir configuré l'application sur votre téléphone.

## 2. Comment inscrire son numero sur Signal?

- Installez et ouvrez la version la plus récente de Signal sur votre appareil Android ou iOS.
- Prenez connaissance des Conditions générales et des règles de confidentialité et appuyez sur Continuer pour les accepter.
- Saisissez et confirmez votre numéro de téléphone.
- Appuyez sur Continuer (sur Android) ou Suivant (sur iOS).
- Appuyez sur « OK » pour confirmer votre numéro de téléphone.
- Vous recevrez un code de vérification par SMS. Si vous ne pouvez pas recevoir de SMS, vous pouvez aussi demander un appel de vérification. Une fois le compte à rebours terminé, appuyez sur Appelez-moi.
- Si le code de vérification n’est pas détecté automatiquement, vous pouvez le saisir manuellement. 
Suivez les instructions à l’écran pour terminer le processus d’inscription.

[Résolution des problèmes](https://support.signal.org/hc/fr/articles/360007318751-R%C3%A9solution-des-probl%C3%A8mes-d-inscription)

### 3. Importation des contacts

- **Accès aux contacts** : Signal vous demandera l'autorisation d'accéder à vos contacts. Accordez cette autorisation pour que vos amis utilisant Signal apparaissent dans votre liste de contacts.
- **Inviter des amis** : Si vos amis n'ont pas encore Signal, vous pouvez les inviter à rejoindre l'application en utilisant leur numéro de téléphone ou un lien.

[Contacts](https://support.signal.org/hc/fr/articles/360007319011-G%C3%A9rer-les-contacts-les-pseudos-et-les-notes#contacts_icon)

## Sauvegarder ses conversations WhatsApp

### Sur Android

1. Ouvrez WhatsApp et allez dans le chat que vous souhaitez exporter
2. Appuyez sur les trois points verticaux en haut à droite
3. Sélectionnez "Plus" puis "Exporter la conversation"
4. Choisissez d'inclure ou non les médias
5. Sélectionnez l'application avec laquelle vous voulez partager le fichier (email, Google Drive, etc.)

### Sur iPhone

1. Ouvrez le chat WhatsApp à exporter
2. Appuyez sur le nom du contact en haut
3. Faites défiler vers le bas et sélectionnez "Exporter la conversation"
4. Choisissez d'inclure ou non les médias
5. Sélectionnez la méthode de partage (email, Notes, Fichiers, etc.)

### Conseils supplémentaires

- L'export inclut jusqu'à 40 000 messages sans médias ou 10 000 avec médias
- Le fichier exporté est au format .txt ou .zip
- Pour une sauvegarde complète, utilisez la fonction de sauvegarde intégrée de WhatsApp
- Des outils tiers comme MobileTrans permettent d'exporter facilement vers PDF

N'oubliez pas que l'export ne remplace pas une sauvegarde complète. Pensez à sauvegarder régulièrement l'ensemble de vos données WhatsApp.