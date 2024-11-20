# 1. Définir une image de base Node.js
FROM node:22-alpine

# 2. Définir le répertoire de travail dans le conteneur
WORKDIR /app

# 3. Copier les fichiers nécessaires dans le conteneur
COPY package*.json ./
COPY . .

# 4. Installer les dépendances
RUN npm install

# 5. Exposer le port utilisé par l'application (par exemple, 3000)
EXPOSE 3000

# 6. Définir la commande pour exécuter l'application
CMD ["node", "app.js"]
