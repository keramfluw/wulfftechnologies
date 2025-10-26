# Wulff Technologies Ltd Website

This repository contains the static website for **Wulff Technologies Ltd**.

## Deployment on Vercel

1. Go to https://vercel.com and sign in.
2. Click **New Project** → **Import Git Repository**.
3. Choose this repository and click **Deploy**.
4. Add your custom domain `wulfftechnologies.com` under Project → Settings → Domains.
5. Add the following DNS record at your domain registrar (web.de):

   ```
   Type: A
   Name: @
   Value: 76.76.21.21
   ```

   Optional (for www):
   ```
   Type: CNAME
   Name: www
   Value: cname.vercel-dns.com
   ```

6. Wait for DNS propagation and enjoy your secure live site.
