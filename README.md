# Respositorio-de-invitacion-de-cumplea-os
Cumpleaños
cd "C:\Users\famil\OneDrive\Desktop"

git clone https://github.com/ingridjle98-rgb/Respositorio-de-invitacion-de-cumplea-os.git "invitacion-github"

Copy-Item ".\Tarjetas\index.html" ".\invitacion-github\index.html"
Copy-Item ".\Tarjetas\sporting-logo.svg" ".\invitacion-github\sporting-logo.svg"

cd ".\invitacion-github"

git add index.html sporting-logo.svg
git commit -m "Publicar invitación de cumpleaños de Lautaro"
git push origin main
