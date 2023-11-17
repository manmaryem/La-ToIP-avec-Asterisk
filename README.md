# La-ToIP-avec-Asterisk

# Etape 1: Installation d'Asterisk sur Ubuntu :

## Mettez à jour le système
sudo apt update
sudo apt upgrade

# Installez Asterisk
sudo apt install asterisk

![image](https://github.com/manmaryem/La-ToIP-avec-Asterisk/assets/137881827/110f119a-658c-4751-a26e-0a6e69c7f774)

- 2) Téléchargez la dernière version d’Asterisk à l’aide de la commande ci-dessous :wget
  ![image](https://github.com/manmaryem/La-ToIP-avec-Asterisk/assets/137881827/7450bce5-b5d7-45eb-b970-62e298d7e1d6)

 # Installer Asterisk
 
 - Le script effectuera diverses vérifications pour s’assurer que toutes les dépendances de votre système sont présentes. Vous pouvez démarrer le script en tapant :configure

sudo ./configure
Une fois l’opération terminée, vous verrez la sortie ci-dessous :

![image](https://github.com/manmaryem/La-ToIP-avec-Asterisk/assets/137881827/57c18fdc-4110-4263-b256-24550c43c2c5)

#### Sélectionnez ensuite les modules que vous souhaitez compiler et installer. Ensuite, accédez au système de sélection de menu en tapant la commande suivante :

##### sudo make menuselect
- Après avoir téléchargé les fichiers sources MP3, vous devrez demander à Asterisk de construire le module MP3. Pour ce faire, sélectionnez :format_mp3
  ![image](https://github.com/manmaryem/La-ToIP-avec-Asterisk/assets/137881827/8119bf5f-0cbf-413c-8a60-0f9060637ab7)
  
![image](https://github.com/manmaryem/La-ToIP-avec-Asterisk/assets/137881827/777c5e0a-e197-40ee-bd4d-22b92ec8c249)

# L’étape suivante consiste à installer Asterisk et ses modules en exécutant la commande suivante :

##### sudo make install

![image](https://github.com/manmaryem/La-ToIP-avec-Asterisk/assets/137881827/3e450a7b-0885-4ecf-8299-f4a0e566e15f)
![image](https://github.com/manmaryem/La-ToIP-avec-Asterisk/assets/137881827/d441960f-c8c0-4329-be7d-f4a1cdb34a5b)

# Étape 2 : Configuration de l'utilisateur Stéphane Groot

- Fichier de configuration principal d'Asterisk
- Le fichier principal de configuration d'Asterisk est sip.conf. Utilisons-le pour configurer l'utilisateur Stéphane Groot.
  # Ouvrez le fichier sip.conf
sudo nano /etc/asterisk/sip.conf
![image](https://github.com/manmaryem/La-ToIP-avec-Asterisk/assets/137881827/60f66b60-07c6-4e82-9a03-a1ccbfe9f9ea)

### sudo service asterisk restart








