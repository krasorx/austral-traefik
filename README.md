# austral-traefik
Configuración traefik para VPS con varios endpoint
cp .env.development .env
Para generar la password traefik
echo $(htpasswd -nb admin password) | sed -e s/\\$/\\$\\$/g
chmod 600 opt/acme.json
