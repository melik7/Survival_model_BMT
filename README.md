# Survival_model_BMT
Bone Marrow Transplantation survival model and data exploration


Contexte de l'étude

L'ensemble de données décrit des patients pédiatriques atteints de plusieurs maladies hématologiques : troubles malins (par exemple, leucémie lymphoblastique aiguë, leucémie aiguë myéloïde, leucémie myéloïde chronique, syndrome myélodysplasique) et cas non malins (par exemple, anémie aplasique sévère, anémie de Fanconi, avec adrénoleucodystrophie liée à l'X). Tous les patients ont été soumis à une greffe allogénique non manipulée de cellules souches hématopoïétiques d'un donneur.

Le dataset est contitué de 187 instances et de 39 attributs. De plus il contient des valeurs manquantes

Quelques variables importantes du jeu de données :
- Les informations concernant le donneur et le réceveur (age, sexe, groupe sanguin, IMC, …)
- Des données sanguines plus spécifiques au receveur (dosage des cellules CD34+ et CD3+, le temps pour récupérer des valeurs plaquettaire et de neutrophile normale, …)
- HLA_match - Compatibilité des antigènes du donneur et du receveur de cellules souches hématopoïétiques (score sur 10)
- La source des cellules souches : sang périphérique ou moelle osseuse
- Des données qui permettent d’évaluer la réussite de la greffe comme par exemple le temps et le statut de survie, l’événement de rechute, ou encore le temps avant le développement d'une maladie aiguë du greffon.
