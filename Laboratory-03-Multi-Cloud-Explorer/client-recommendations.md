# Client Recommendations & Decision Matrix

## Client A — Startup Company
**Recommended Platform: AWS**

AWS is ideal for startups because its Free Tier lowers initial costs while the broad service catalog and auto-scaling let infrastructure grow seamlessly alongside user adoption. Pay-as-you-go pricing aligns expenses with revenue, and services reduce management overhead.

**Recommended Services:**
1. **Amazon EC2** — scalable virtual servers for application logic
2. **Amazon S3** — low-cost, durable storage for app assets and user data
3. **Amazon RDS** — managed database to avoid administration overhead

---

## Client B — University (Microsoft Stack)
**Recommended Platform: Microsoft Azure**

Azure is the natural choice because it integrates natively with Windows Server, Active Directory, and Microsoft 365 — preserving existing identities, security policies, and licensing investments. The university can migrate services gradually without rebuilding architecture.

**Recommended Services:**
1. **Azure Virtual Machines** — lift-and-shift Windows workloads directly
2. **Microsoft Entra ID** — extend campus identities to cloud resources
3. **Azure SQL Database** — migrate campus databases without SQL rewrite

---

## Client C — AI Research Company
**Recommended Platform: Google Cloud Platform (GCP)**

GCP leads in AI and high-performance computing — Google's own research heritage powers Vertex AI, TensorFlow compatibility, and custom TPUs that accelerate model training far beyond standard GPUs. BigQuery also enables unified analysis of massive research datasets.

**Recommended Services:**
1. **Vertex AI** — end-to-end ML platform for building and deploying models
2. **Compute Engine with GPUs/TPUs** — high-performance computing for research
3. **BigQuery** — serverless data warehouse for research datasets and analytics

---

## Client D — Global E-Commerce Company
**Recommended Platform: AWS**

AWS has the largest global infrastructure footprint with the most regions — critical for low-latency worldwide shopping experiences. Proven auto-scaling, mature load balancing, and enterprise-grade reliability match the unpredictable traffic spikes of global e-commerce.

**Recommended Services:**
1. **Amazon EC2 + Auto Scaling Groups** — automatically scale during sales events
2. **Amazon S3 + CloudFront** — global, fast delivery of product images and assets
3. **Amazon RDS (Multi-AZ)** — highly available database for orders and customers

---

## — Multi-Cloud Decision Matrix —

| Business Requirement | Recommended Platform | Justification |
|---|---|---|
| Startup Company | AWS | Free Tier, broad services, community support; scales from prototype to global |
| Enterprise Organization | AWS or Azure | AWS for widest capabilities; Azure if Microsoft stack is already in place — both offer enterprise compliance |
| Microsoft Environment | Azure | Native Windows, 365, .NET, and SQL Server integration; minimal migration friction |
| AI / Machine Learning | GCP | Vertex AI, TPUs, and TensorFlow ecosystem; built on Google's own AI infrastructure |
| Kubernetes Deployment | GCP (GKE) | Google created Kubernetes; GKE remains the most mature managed offering |
| Global Web Application | AWS | Most regions and Availability Zones; mature auto-scaling and CDN |
