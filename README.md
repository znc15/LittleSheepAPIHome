# LittleSheepAPIHome

## Deployment

This repository now supports deployment through GitHub Actions to:

- GitHub Pages (`.github/workflows/deploy-pages.yml`)
- Tencent Cloud EdgeOne Pages (`.github/workflows/deploy-edgeone.yml`)
- Alibaba Cloud ESA (`.github/workflows/deploy-esa.yml`)

### Tencent Cloud EdgeOne Pages

Configure these repository secrets:

- `EDGEONE_API_TOKEN`: EdgeOne API token
- `EDGEONE_PROJECT_NAME`: EdgeOne Pages project name

Workflow: **Deploy to Tencent EdgeOne**

### Alibaba Cloud ESA

Configure these repository secrets:

- `ESA_ACCESS_KEY_ID`: Alibaba Cloud AccessKey ID
- `ESA_ACCESS_KEY_SECRET`: Alibaba Cloud AccessKey Secret
- `ESA_PROJECT_NAME`: ESA Functions & Pages project name

Workflow: **Deploy to Alibaba Cloud ESA**
