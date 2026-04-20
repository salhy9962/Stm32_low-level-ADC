Low-Level STM32 Programming – ADC & Register Addressing
📌 Description

Ce projet consiste en la programmation bas niveau d’un microcontrôleur STM32 en utilisant directement l’adressage des registres (register-level programming).

L’objectif est de lire une valeur analogique à partir d’un potentiomètre via l’ADC, puis d’utiliser cette valeur pour contrôler l’allumage des LEDs intégrées sur la carte STM32.

⚙️ Fonctionnement
🎚️ Le potentiomètre génère une tension analogique variable
🔄 Le convertisseur ADC du STM32 convertit cette tension en valeur numérique
💡 Selon la valeur convertie :
Une ou plusieurs LEDs s’allument
Chaque intervalle correspond à une LED spécifique
🧠 Concepts abordés
🧩 Adressage direct des registres
Manipulation des registres via leurs adresses mémoire
Configuration sans utiliser de bibliothèques HAL
⚙️ Configuration bas niveau :
Activation de l’horloge (RCC)
Configuration GPIO (mode analogique / sortie)
Configuration ADC (résolution, canal, conversion)
🔄 Lecture et traitement des données ADC
🛠️ Technologies utilisées
STM32F407 discovery
Langage C (bas niveau – registres)
ADC (Analog-to-Digital Converter)
GPIO (LEDs)
Potentiomètre
🚀 Résultat
Contrôle en temps réel des LEDs selon la position du potentiomètre
Compréhension approfondie du fonctionnement interne du STM32
Maîtrise de la programmation sans abstraction (sans HAL).
