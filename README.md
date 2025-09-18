# hdwright

Site web pour la fondation H. Dudley Wright

## Deploiement automatique

Ce projet est configure pour se deployer automatiquement sur **hdwright.bionicable.ch** a chaque push sur la branche `main`.

### URL d'acces
- **Production**: https://hdwright.bionicable.ch
- **Gestion**: https://deploy.bionicable.ch

### Webhook configure
- **URL**: https://deploy.bionicable.ch/webhook/github
- **Secret**: Configure automatiquement
- **Events**: Push, Repository

## Developpement

1. Cloner le projet:
   ```bash
   git clone https://github.com/lucaslattion/hdwright.git
   cd hdwright
   ```

2. Modifier les fichiers selon vos besoins

3. Commiter et pousser:
   ```bash
   git add .
   git commit -m "Mise a jour du site"
   git push origin main
   ```

4. Le deploiement se fait automatiquement 

---

Powered by bionicable.ch deployment system
