✅ Traefik v3
✅ AWS Route53 (for DNS-01 challenge + wildcards)
✅ Let’s Encrypt certificates
✅ One sample container served over HTTPS on a subdomain
(e.g. app.yourdomain.com)

Everything is self-contained and ready to use.

Directory structure
project/
│
├── docker-compose.yml
└── letsencrypt/
    └── acme.json   (will be created automatically)


Prepare permissions
mkdir letsencrypt
touch letsencrypt/acme.json
chmod 600 letsencrypt/acme.json
