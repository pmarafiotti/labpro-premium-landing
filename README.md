# LabPRO Premium — Landing de produção (hero-v5)

Landing de vendas do **LabPRO Premium**. Site estático (um único `index.html`).

- **Domínio:** labpropremium.nutrirenatafantinati.com.br (CNAME → cname.vercel-dns.com)
- **Hospedagem:** Vercel (Git integration → deploy automático a cada push)
- **Tracking:** o container GTM-524RHSNF está embutido no `index.html` (head + body),
  pois o subdomínio não herda o GTM site-wide do WordPress. Dispara pixel + forwarding.
- **Checkout:** pay.hotmart.com/M97618726I?off=j4k3bie5&checkoutMode=10 (o forwarding reescreve).

Fonte/edição: `dashboard/landing/labpro-premium-hero-v5.html` no repo trafego-ph-dashboard.
