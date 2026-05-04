# nsoua-app
application mobile de gestion IMMOBILIÈRE  et sécurité immobilier 
# 🏠 N'SOUA — Je veille sur toi

> Application mobile de gestion immobilière et de sécurité communautaire 
> pour l'Afrique francophone

[![Flutter](https://img.shields.io/badge/Flutter-3.24-blue)]()
[![Supabase](https://img.shields.io/badge/Supabase-2.0-green)]()
[![License](https://img.shields.io/badge/License-Propriétaire-red)]()

## 🎯 Mission

Digitaliser la relation locataire-propriétaire et créer le premier réseau 
communautaire d'alerte hors ligne en Afrique.

## ✨ Fonctionnalités

### 🏘️ Gestion locative
- Contrats de bail numériques signés électroniquement
- Paiement de loyer via Wave, Orange Money, MTN MoMo
- Reçus PDF automatiques
- Rappels de paiement intelligents
- Tableau de bord propriétaire/locataire

### 💬 Communication
- Messagerie temps réel locataire ↔ propriétaire
- Envoi de documents
- Notifications push

### 🆘 Sécurité hors ligne (cœur du projet)
- Bouton SOS (3 pressions volume bas)
- Mot-clé vocal "N'SOUA"
- Détection de secousse
- Envoi SMS natif vers contacts + police (170)
- Diffusion Bluetooth LE + Wi-Fi Direct aux voisins
- Alertes communautaires géolocalisées

## 💰 Modèle économique

| Cible | Tarif |
|-------|-------|
| Locataires | **Gratuit à vie** |
| Alerte d'urgence | **Gratuit pour tous** |
| Propriétaires (1 bien) | Gratuit |
| Propriétaires (2-5 biens) | 2 000 FCFA/mois |
| Propriétaires (6+ biens) | 5 000 FCFA/mois |
| Commission paiement loyer | 1% (plafonné à 2 000 FCFA) |

## 🛠️ Stack technique

- **Mobile** : Flutter 3.24 (Dart)
- **Backend** : Supabase (PostgreSQL + Auth + Realtime + Storage)
- **Paiement** : Wave API, CinetPay (agrégateur Orange/MTN/Moov)
- **Notifications** : Firebase Cloud Messaging
- **Cartes** : OpenStreetMap (gratuit) via flutter_map
- **PDF** : syncfusion_flutter_pdf
- **Hors ligne** : flutter_blue_plus + nearby_connections + sms_advanced

## 📂 Structure
