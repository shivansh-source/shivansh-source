<!-- ================= HERO ================= -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=220&section=header&text=Shivansh%20Sinha&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=38"/>
</p>

<p align="center">
  <b>Cloud-Native Developer &middot; Open Source Contributor &middot; Go &amp; Kubernetes</b><br/>
  <sub>Working on production controllers, provider frameworks, and test infrastructure across CNCF projects</sub>
</p>

<p align="center">
  <a href="https://github.com/shivansh-source">
    <img src="https://img.shields.io/github/followers/shivansh-source?label=Followers&style=for-the-badge"/>
  </a>
  <a href="https://github.com/shivansh-source?tab=repositories">
    <img src="https://img.shields.io/github/stars/shivansh-source?label=Stars&style=for-the-badge"/>
  </a>
  <a href="https://linkedin.com/in/shivansh-sinha-167304307">
    <img src="https://img.shields.io/badge/LinkedIn-Profile-blue?style=for-the-badge"/>
  </a>
</p>

---

## About

Founding engineer at **Capmob Financial Services** in Bengaluru, building the backend and infrastructure from scratch for a global digital lending platform &mdash; Go services on AWS ECS Fargate, Terraform-provisioned infrastructure, CodeBuild CI/CD, and observability through CloudWatch and EventBridge.

Outside work I contribute Go and Kubernetes code across CNCF projects &mdash; **Open Cluster Management, kro, KubeStellar, OpenEverest**. The pattern is usually the same: read the code, reproduce the issue, write the test that captures it, iterate with maintainers until it lands.

---

## Technical focus

**Kubernetes controllers.** controller-runtime reconcile loops, kubebuilder RBAC markers, client-go clientsets and informers, CRD authoring, provider-framework work in OpenEverest v2 (`provider-runtime`, `BackupProvider`, `parametersSchema`/`uiSchema`), and the Open Cluster Management klusterlet-agent surface.

**Testing infrastructure.** Table-driven Go tests, controller-runtime fake client, `httptest`, Ginkgo/Gomega for end-to-end suites, chainsaw for integration testing, envtest, and release-parameterised GitHub Actions workflows for CI.

**Backend and infrastructure.** Go services, PostgreSQL and MySQL, Docker, Helm chart authoring, and cloud infrastructure through Terraform on AWS (ECS Fargate, ECR, ALB, VPC, RDS/Aurora).

<p>
  <img src="https://skillicons.dev/icons?i=go,kubernetes,docker,githubactions,terraform,aws,postgresql,linux,git&theme=dark"/>
</p>

---

## Open source

**Open Cluster Management (CNCF).** Added TLS profile configuration to the klusterlet controller in [ocm#1486](https://github.com/open-cluster-management-io/ocm/pull/1486) &mdash; new `TLSMinVersion` and `TLSCipherSuites` fields on `klusterletConfig`, a ConfigMap-driven `populateTLSConfig()` in the reconcile path, flag injection into three agent deployments and updated controller tests. Co-authored a ManifestWorkReplicaSet fix with a maintainer in [ocm#1421](https://github.com/open-cluster-management-io/ocm/pull/1421), moving generated ManifestWorks to `GenerateName`.

**kro (CNCF).** Authored [KREP-008](https://github.com/kro-run/kro/pull/933), an accepted enhancement proposal for resource-backed `includeWhen` evaluation, subsequently implemented by a maintainer.

**KubeStellar (CNCF Sandbox).** Merged PRs across `kubestellar/kubestellar`, `kubestellar/kubeflex` and `kubestellar/kubestellar-killercoda`, including a Kubernetes 1.32 platform uplift ([#3726](https://github.com/kubestellar/kubestellar/pull/3726), regenerated client-go clientsets, informers and listers for five CRDs alongside CRD bases, Helm chart and CI workflows) and a release-parameterised end-to-end test workflow in KubeFlex ([#594](https://github.com/kubestellar/kubeflex/pull/594)). Three months as a QA intern on the KubeStellar Console: filed a large volume of bug reports, coverage-gap findings and performance issues; authored `httptest` and WebSocket integration coverage for the agent server in [console#939](https://github.com/kubestellar/console/pull/939).

**OpenEverest (CNCF Sandbox).** Contributed a `BackupProvider` implementation for the ClickHouse provider in [provider-altinity-clickhouse#22](https://github.com/openeverest/provider-altinity-clickhouse/pull/22) &mdash; resolves the v2 `BackupStorage` S3 contract into clickhouse-backup, with kubebuilder RBAC markers and table-driven tests against the controller-runtime fake client. Delivered proxy support for Helm chart hook Jobs across six library templates in [helm-charts#77](https://github.com/openeverest/helm-charts/pull/77) (maintainer-assigned), a values-driven `InstancePreset` catalog for `provider-kubeai` in [#8](https://github.com/openeverest/provider-kubeai/pull/8), and a merged fix for a silently-dead CI check in the core repository ([openeverest#2962](https://github.com/openeverest/openeverest/pull/2962)). Filed bug reports across the core and provider repositories concentrated on install and upgrade correctness &mdash; several closed by maintainers.

---

## GitHub activity

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=shivansh-source&theme=tokyonight"/>
</p>

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=shivansh-source&theme=tokyonight"/>
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=shivansh-source&theme=tokyonight"/>
</p>

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=shivansh-source&theme=tokyonight&column=6&no-frame=true&margin-w=6"/>
</p>

---

## Contact

- GitHub: [github.com/shivansh-source](https://github.com/shivansh-source)
- LinkedIn: [linkedin.com/in/shivansh-sinha-167304307](https://linkedin.com/in/shivansh-sinha-167304307)
- Email: shivansh976053@gmail.com

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=120&section=footer"/>
</p>
