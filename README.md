# Object Detection Project

## Description

Ce projet implémente des techniques avancées de détection d'objets en utilisant YOLOv8. Il comprend des fonctionnalités comme le suivi en temps réel des objets dans des vidéos et des flux webcam, ainsi que le comptage des objets spécifiques (ex. voitures, camions, personnes).

---

## Structure du Répertoire

```
├── .gitignore                # Fichiers/dossiers ignorés par Git
├── Images/                   # Images utilisées pour la détection
├── Yolo-Weights/             # Modèles pré-entraînés YOLOv8
├── car_counter.py            # Script pour compter les voitures
├── requirements.txt          # Dépendances nécessaires
├── sort.py                   # Implémentation de l'algorithme SORT
├── videos/                   # Vidéos pour la détection
├── yolo_basics.py            # Script de détection simple
├── yolo_webcam.py            # Script de détection avec webcam/vidéos
```

---

## Installation

1. Clonez ce projet :

   ```bash
   git clone https://github.com/HAS1ELB/Object-Detection.git
   cd Object-Detection
   ```
2. Installez les dépendances :

   ```bash
   pip install -r requirements.txt
   ```
3. Téléchargez les poids YOLOv8 :

   - [yolov8l.pt](https://raw.githubusercontent.com/HAS1ELB/Object-Detection/main/Yolo-Weights/yolov8l.pt)
   - [yolov8n.pt](https://raw.githubusercontent.com/HAS1ELB/Object-Detection/main/Yolo-Weights/yolov8n.pt)

---

## Utilisation

### 1. Détection basique avec une image

Exécutez le fichier `yolo_basics.py` :

```bash
python yolo_basics.py
```

### 2. Détection en temps réel avec une webcam/vidéo

Pour exécuter la détection avec une vidéo :

```bash
python yolo_webcam.py
```

### 3. Comptage d'objets spécifiques

Pour compter les voitures dans une vidéo :

```bash
python car_counter.py
```

---

## Dépendances

- `cvzone`
- `ultralytics`
- `opencv-python`
- Et bien plus (voir `requirements.txt`).

---

## Ressources

- [Documentation officielle de YOLO](https://github.com/ultralytics/ultralytics)
- [Tutoriels OpenCV](https://opencv.org/)

---

## Contributeur

**HASSAN EL BAHRAOUI**
Contact : [GitHub](https://github.com/HAS1ELB)

**WALID EL BACHAR**
Contact : [GitHub](https://github.com/lidwaa)

**Dehbi KAMAL**
Contact : [GitHub](https://github.com/kamaLc73)
