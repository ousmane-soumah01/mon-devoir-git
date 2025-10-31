# 📊 Plan d'Exécution du Projet Vision Macro Ousmane (2025-2028)

Ce diagramme présente l'enchaînement des tâches par composante, y compris le pilotage continu (Composante 4).

```mermaid
gantt
    title Diagramme de Gantt - Vision Macro Ousmane (2025-2028)
    dateFormat  YYYY-MM
    axisFormat  %b %Y

    section Composante 4: Pilotage & Clôture (Transversal)
    Management & Coordination continue :active, management, 2025-10, 34m
    Clôture administrative & financière :c4_cloture, after c3_exec, 1m

    section Composante 1: Networking
    1. Cartographie                   :active, c1_carto, 2025-11, 5m
    Plan de communication             :c1_com, 2025-11, 2m
    COPIL 1                           :milestone, 2025-12, 0d
    COPIL 2 (Validation C1)           :milestone, c1_fin, after c1_carto, 0d

    section Délai (Préparation C2)
    Période de transition             :c2_debut, after c1_fin, 7m

    section Composante 2: Accompagnement
    2. Mobilisation acteurs           :active, c2_mob, after c2_debut, 4m
    3. Atelier de partage             :c2_partage, after c2_mob, 4m
    4. Renforcement capacités         :c2_renfort, after c2_partage, 4m
    COPIL 3 (Validation C2)           :milestone, c2_fin, after c2_renfort, 0d

    section Composante 3: Plaidoyer
    5. Conception plan plaidoyer      :active, c3_concep, after c2_fin, 4m
    6. Exécution plaidoyer            :c3_exec, after c3_concep, 3m
    COPIL 4 (Clôture Finale)          :milestone, after c3_exec, 0d
