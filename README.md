# Linux Bootcamp — Cloud Engineer 2030
**Étudiant :** Taha TOUFIK | **Objectif :** Cloud Engineer / AWS Solutions Architect  
**Rythme :** 1h–1h30 par jour | **Durée estimée :** 10–12 semaines | **Mis à jour :** 2026-06-02

---

## Pourquoi ce curriculum ?

Ce bootcamp couvre le **minimum viable Linux** pour un Cloud Engineer en 2030 :
- Administrer des instances EC2, EKS nodes, conteneurs
- Écrire des scripts d'automatisation et des User Data AWS
- Diagnostiquer et sécuriser des serveurs en production
- Préparer AWS Solutions Architect Associate + CKA

---

## Curriculum & Progression

### Phase 1 — Fondations (Semaines 1–2)

| # | Module | Statut | Date |
|---|--------|--------|------|
| 01 | Introduction & Architecture Linux | ⬜ À faire | |
| 02 | Terminal, Shell & Commandes Essentielles | ⬜ À faire | |
| 03 | Navigation & Manipulation du Système de Fichiers | ⬜ À faire | |
| 04 | Fichiers Texte (cat, less, vim, nano) | ⬜ À faire | |
| 05 | Stdin / Stdout / Stderr & Redirection | ⬜ À faire | |

### Phase 2 — Administration Système (Semaines 3–5)

| # | Module | Statut | Date |
|---|--------|--------|------|
| 06 | Utilisateurs, Groupes & Sudo | ⬜ À faire | |
| 07 | Permissions, Ownership & ACL | ⬜ À faire | |
| 08 | Processus & Gestion des Tâches | ⬜ À faire | |
| 09 | Services & Daemons — Systemd | ⬜ À faire | |
| 10 | Gestion des Paquets (apt, dnf, rpm) | ⬜ À faire | |

### Phase 3 — Réseau & Sécurité (Semaines 6–8)

| # | Module | Statut | Date |
|---|--------|--------|------|
| 11 | Réseau Linux (ip, firewall, DNS, curl) | ⬜ À faire | |
| 12 | SSH & Accès Distant Sécurisé | ⬜ À faire | |
| 13 | Sécurité Linux & Hardening | ⬜ À faire | |

### Phase 4 — Stockage & Performance (Semaines 8–9)

| # | Module | Statut | Date |
|---|--------|--------|------|
| 14 | Stockage, Disques & LVM | ⬜ À faire | |
| 15 | Monitoring & Performance Système | ⬜ À faire | |

### Phase 5 — Scripting & Automatisation (Semaines 9–10)

| # | Module | Statut | Date |
|---|--------|--------|------|
| 16 | Bash Scripting — Fondamentaux | ⬜ À faire | |
| 17 | Text Processing Avancé (grep, sed, awk, jq) | ⬜ À faire | |

### Phase 6 — Cloud Linux (Semaines 11–12)

| # | Module | Statut | Date |
|---|--------|--------|------|
| 18 | Variables d'Environnement & Configuration | ⬜ À faire | |
| 19 | Linux pour le Cloud (cloud-init, IMDS, SSM, AWS CLI) | ⬜ À faire | |
| 20 | Projet Final — Serveur Web Sécurisé sur EC2 | ⬜ À faire | |

**Légende :** ⬜ À faire | 🔄 En cours | ✅ Terminé

---

## Structure de chaque module

```
XX-nom-module/
├── cours.md       ← Théorie + concepts clés + commandes
├── exercices.md   ← Hands-On pratiques (sur EC2 ou VM locale)
└── quiz.md        ← Quiz de validation (5–8 questions)
```

---

## Prérequis pour passer à la suite

Avant de commencer Docker, AWS Solutions Architect, ou Kubernetes, tu dois être capable de :

| Compétence | Module | Niveau attendu |
|---|---|---|
| Se connecter à un serveur Linux via SSH | 12 | Autonome |
| Naviguer et manipuler le filesystem | 03 | Autonome |
| Créer/modifier des utilisateurs et permissions | 06, 07 | Autonome |
| Démarrer/arrêter/monitorer des services | 09 | Autonome |
| Écrire un script Bash de base | 16 | Fonctionnel |
| Diagnostiquer un problème réseau | 11 | Fonctionnel |
| Monter un disque EBS et étendre un volume LVM | 14 | Fonctionnel |
| Lire les logs et monitorer les ressources | 15 | Fonctionnel |
| Écrire un User Data script pour EC2 | 19 | Fonctionnel |

---

## Connexions avec les certifications

| Module Linux | Certification ciblée | Utilisation concrète |
|---|---|---|
| 01–07 | AWS Cloud Practitioner | Comprendre EC2, IAM, Linux OS |
| 08, 09, 15 | AWS SAA | Troubleshoot instances EC2, CloudWatch |
| 11, 12 | AWS SAA | Security Groups, NACLs, SSH key pairs |
| 13 | AWS SAA + Security Specialty | IAM, hardening, NCA compliance |
| 14 | AWS SAA | EBS, EFS, instance storage |
| 16, 17 | AWS DevOps Professional | Scripts CI/CD, User Data |
| 18, 19 | Tous | AWS CLI, cloud-init, SSM |
| 20 | AWS SAA (validation pratique) | Architecture complète |
