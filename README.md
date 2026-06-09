# 3D Modeling & Animation - Teapot and Cup Scene

Ατομική εργασία για τη δημιουργία 3D σκηνής στο Blender, με μοντελοποίηση, φωτισμό, texture painting και animation. Το project περιλαμβάνει δύο cartoon χαρακτήρες, μία τσαγιέρα και ένα φλιτζάνι, που δημιουργήθηκαν από βασικά γεωμετρικά σχήματα και αποδόθηκαν σε τελικό video animation.

## Περιγραφή

Η σκηνή δημιουργήθηκε στο Blender 4.04 και βασίζεται στη μέθοδο της πατιτούρας, με χρήση εικόνων αναφοράς για τη διαμόρφωση των βασικών σχημάτων. Η τσαγιέρα και το φλιτζάνι μοντελοποιήθηκαν κυρίως από cylinders, UV spheres και torus objects, με επεξεργασία σε Edit Mode, loop cuts, scaling και rotation.

Το τελικό αποτέλεσμα περιλαμβάνει:

- cartoon 3D τσαγιέρα με πρόσωπο, χερούλι, καπάκι και στόμιο
- cartoon 3D φλιτζάνι με μάτια, χερούλι και επάνω δαχτυλίδι
- texture painting με custom base color textures
- μεταλλική υφή στα μοντέλα
- φωτισμό και κάμερα για την τελική σκηνή
- animation 121 frames στα 24 fps
- τελικό video αρχείο σε ανάλυση 1920x1080

## Τεχνολογίες και εργαλεία

- Blender 4.04
- 3D Modeling
- Texture Paint
- UV Unwrapping / Smart UV Project
- Subdivision Surface Modifier
- Keyframe Animation
- Video Sequencer
- PNG Image Sequence Rendering

## Διαδικασία υλοποίησης

1. Επιλογή εικόνων αναφοράς για την τσαγιέρα και το φλιτζάνι.
2. Δημιουργία βασικών σωμάτων με cylinder objects.
3. Επεξεργασία των μοντέλων σε Edit Mode με X-Ray, edge loops, loop cuts και scale.
4. Δημιουργία στομίου, χερουλιών και καπακιού με επιλογή faces, rotation και scaling.
5. Προσθήκη UV spheres για μάτια και μάγουλα.
6. Προσθήκη torus objects για στόμα, χείλος φλιτζανιού και λεπτομέρειες καπακιού.
7. Εφαρμογή Subdivision Surface modifier για πιο ομαλή και καμπυλωτή επιφάνεια.
8. UV unwrap και texture painting για τα βασικά χρώματα των αντικειμένων.
9. Ρύθμιση material με metallic `0.500` και roughness `0.400`.
10. Τοποθέτηση κάμερας και φωτισμού.
11. Δημιουργία animation με keyframes ανά 20 frames.
12. Rendering σε PNG sequence και τελική σύνθεση σε video.

## Δομή αρχείων

```text
iis24029/
├── iis24029_1.blend ... iis24029_9.blend
├── iis24029_final.blend
├── iis24029_final.avi
├── iis24029_final.docx
├── outputPhotos/
│   ├── 0001.png
│   ├── ...
│   └── 0121.png
├── Cylinder Base Color*.png
├── Sphere Base Color.png
├── Torus Base Color.png
├── cartoon.jpg
├── εικόνα τσαγιέρας.jpg
└── εικόνα φλιτζανιού.jpg
```

## Αρχεία project

- `iis24029_final.blend`: τελικό Blender project.
- `iis24029_final.avi`: τελικό rendered animation.
- `iis24029_final.docx`: αναφορά με τα βήματα υλοποίησης.
- `iis24029_1.blend` έως `iis24029_9.blend`: ενδιάμεσα στάδια της εργασίας.
- `outputPhotos/`: rendered PNG sequence με 121 frames.
- `*Base Color*.png`: texture paint αρχεία των αντικειμένων.
- `εικόνα τσαγιέρας.jpg`, `εικόνα φλιτζανιού.jpg`: εικόνες αναφοράς.

## Εκτέλεση / Προβολή

Για προβολή ή επεξεργασία του project:

1. Ανοίξτε το `iis24029_final.blend` με Blender 4.04 ή νεότερη έκδοση.
2. Ελέγξτε τη σκηνή από την κάμερα.
3. Για αναπαραγωγή του animation, χρησιμοποιήστε το timeline του Blender ή ανοίξτε το `iis24029_final.avi`.

Για επαναδημιουργία του video από τα frames:

1. Ανοίξτε το Blender.
2. Μεταβείτε στο Video Editing workspace.
3. Επιλέξτε `Add > Image Sequence`.
4. Φορτώστε τις εικόνες από τον φάκελο `outputPhotos/`.
5. Ορίστε frame range `1-121` και frame rate `24 fps`.
6. Κάντε render το animation.

## Σημείωση για GitHub

Το αρχείο `iis24029_final.blend` είναι πολύ μεγάλο για απλό GitHub upload. Για ανέβασμα στο repository προτείνεται χρήση Git LFS για αρχεία `.blend`, `.avi` και μεγάλα rendered assets ή ανέβασμα του τελικού video/large blend ως GitHub Release asset.

## Δημιουργός

Χατζηανδρέου Νικολέτα  
Αριθμός Μητρώου: iis24029
