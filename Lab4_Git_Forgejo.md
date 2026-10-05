# Lab 4 — Git et Forgejo

## 1. Installation de Git
```bash
git --version
```
![Installation de Git](images/lab4/installation_git.png)

## 2. Configuration de Git
```bash
git config --list
```
![Configuration](images/lab4/configuration_git.png)

## 3. Docker
```bash
docker --version
```
![Version Docker](images/lab4/version_docker.png)

## 4. Volume Forgejo
```bash
sudo docker volume create forgejo_data
```
![Volume Forgejo](images/lab4/creation_volume_forgejo.png)

## 5. Conteneur Forgejo
```bash
sudo docker ps
```
![Conteneur](images/lab4/sudo docker ps.png)

## 6. Dépôt Forgejo
![Dépôt tp-forgejo](images/lab4/rahma_raddadi tp-forgejo.png)

## 7. Trois commits
```bash
git log --oneline
```
![Historique](images/lab4/git log oneline.png)

## 8. Publication
```bash
git push -u origin master
```
![Publication](images/lab4/git push.png)

## 9. Clonage
```bash
git clone http://10.0.2.15:3000/rahma_raddadi/tp-forgejo.git
```
![Clonage](images/lab4/git clone http ....png)

## 10. Synchronisation
La synchronisation finale a donné :
```text
Everything up-to-date
```

## Conclusion
Ce laboratoire a permis de mettre en pratique Git, Docker et Forgejo, puis de publier, cloner et synchroniser un dépôt.
