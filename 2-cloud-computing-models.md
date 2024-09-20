# Module 2 - Cloud Computing models

## Service Models

### IaaS (Infrastructure as a Service) 🖥️
- **Persona**: System Admin (more complex) → Leasing a car
- **Components**:
  - Physical data centers
  - Compute, memory, storage
  - Network

**Typical Use Cases**:
- Quick setup of test and development environments. 🚀
- Business continuity and disaster recovery. 🔒
- Faster deployments and scaling on demand. 📈
- High-performance computing and big data analysis. 📊

**Cons**:
- Lack of transparency in cloud infrastructure configuration and management. ❓
- Dependence on a third party. ⚠️

---

### PaaS (Platform as a Service) 🛠️
- **Persona**: Developer → Renting a car
- **User Responsibilities**: Application code (Develop, Deploy, Run, Manage)

**Components**:
- Servers
- Network
- Storage
- Operating system
- Application runtime
- APIs
- Middleware
- Databases

**Advantages**:
- High level of abstraction, simplifying deployment. 🌟
- Rapid deployment mechanisms and middleware capabilities.

**Use Cases**:
- API development and management. 🔗
- Internet of Things (IoT). 🌐
- Business analytics/intelligence.
- Business process management (BPM).
- Master data management.

**Examples**:
- AWS Elastic Beanstalk
- Cloud Foundry
- IBM Cloud Paks
- Azure
- OpenShift

**Risks**:
- Information security threats. 🔒
- Dependency on service provider infrastructure. ⚠️
- Limited control over changes made by the provider. 🔄

---

### SaaS (Software as a Service) 📱
- **Persona**: End user (less complex) → Taxi

**Supports**:
- Email and collaboration tools, CRM, HR management. 📧

**Key Characteristics**:
- Multitenant architecture.
- Manage privileges and monitor data. 📊
- Security, compliance, and maintenance. 🔐
- Customizable through upgrades.
- Subscription model with scaling options. 💰

**Key Benefits**:
- Faster time from decision to value. ⏱️
- Increased workforce productivity. 💼
- Access core business apps from anywhere. 🌍
- Quick app deployment. ⚡
- Spread software costs over time. 📉

**Use Cases**:
- Reduce premium IT infrastructure and CapEx.
- Avoid ongoing upgrades, maintenance, and patching.
- Run applications with minimal input.
- Manage websites, marketing, sales, and operations. 📈
- Ensure resilience and business continuity via cloud provider. 🔄

**Concerns**:
- Data ownership and safety. 🔍
- Security. 🔒
- Need for a good network connection. 🌐

---

## Deployment Models 🏗️

Deployment models indicate where the infrastructure resides, who owns and manages it, and how cloud resources are made available to users.

### 1. Public Cloud 🌏
- **Characteristics**:
  - Users access resources via web consoles and APIs (e.g., AWS, Azure, IBM Cloud).
  - Cost savings; users don’t own resources.
  - No control over infrastructure.

**Benefits**:
- On-demand resources and economies of scale. 📉
- Highly available.

**Concerns**:
- Security and data sovereignty. 🔐

**Use Cases**:
- Reduce time to market. ⏱️
- Handle fluctuating capacity.
- Secondary infrastructure for disaster recovery. 🔄

---

### 2. Private Cloud 🔒
- **Characteristics**:
  - Exclusive use by a single organization, can be internal or external (e.g., Virtual Private Cloud).

**Benefits**:
- Controlled by internal IT. 🛡️
- Better scalability and security.

**Use Cases**:
- Modernize in-house applications. 🔄
- Full control over security and compliance.

---

### 3. Hybrid Cloud ⚖️
- **Characteristics**:
  - Connects on-premise private cloud and third-party public cloud.

**Benefits**:
- Flexibility; workloads move freely. 🌊
- Combines advantages of both public and private clouds.

**Cons**:
- Complexity in deployment and maintenance. ⚙️

**Use Cases**:
- SaaS integration, data and AI integration, legacy app enhancement.

---

### 4. Community Cloud 🏥
- **Characteristics**:
  - Provisioned for use by a community of organizations with shared concerns (e.g., healthcare organizations).
