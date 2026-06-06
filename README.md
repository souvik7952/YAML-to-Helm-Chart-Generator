<h1>Kubernetes YAML to Helm Chart Generator</h1>

<p>
The Kubernetes YAML to Helm Chart Generator is a browser-based application designed to automate the conversion of Kubernetes manifest files into production-ready Helm charts. The tool helps DevOps engineers, Kubernetes administrators, platform teams, and developers accelerate Helm adoption by eliminating manual template creation and configuration management tasks.
</p>

<h2>Project Overview</h2>

<p>
This application accepts one or multiple Kubernetes YAML files and automatically analyzes, validates, and transforms them into a structured Helm chart package. It intelligently extracts configurable parameters, generates Helm templates, creates values files, and provides validation insights to ensure deployment readiness.
</p>

<h2>Key Features</h2>

<ul>
    <li>Multi-file Kubernetes YAML upload support</li>
    <li>Drag-and-drop file and folder import</li>
    <li>Automatic Kubernetes resource discovery</li>
    <li>Deployment, Service, Ingress, HPA, PVC support</li>
    <li>Automated Helm template generation</li>
    <li>Dynamic values.yaml creation</li>
    <li>Environment-specific configuration generation</li>
    <li>Development, UAT, and Production values files</li>
    <li>Real-time YAML syntax highlighting</li>
    <li>Best-practice validation engine</li>
    <li>Health probe detection</li>
    <li>Resource limit and request validation</li>
    <li>Service selector verification</li>
    <li>Deployment readiness scoring</li>
    <li>Code search and navigation</li>
    <li>Dark and Light theme support</li>
    <li>Workspace explorer with file tree navigation</li>
    <li>One-click Helm chart ZIP export</li>
    <li>Completely browser-based execution</li>
    <li>No backend server required</li>
    <li>Offline-capable architecture</li>
</ul>

<h2>How It Works</h2>

<ol>
    <li>User uploads Kubernetes YAML manifests.</li>
    <li>The parser analyzes all Kubernetes resources.</li>
    <li>The engine identifies configurable values such as images, replicas, ports, resources, and ingress hosts.</li>
    <li>Static values are converted into Helm template variables.</li>
    <li>A complete Helm chart structure is generated.</li>
    <li>Validation rules check for common deployment issues.</li>
    <li>Readiness scores and recommendations are displayed.</li>
    <li>The generated chart can be exported as a ZIP package.</li>
</ol>

<h2>Generated Output</h2>

<p>
The application automatically generates:
</p>

<ul>
    <li>Chart.yaml</li>
    <li>values.yaml</li>
    <li>values-dev.yaml</li>
    <li>values-uat.yaml</li>
    <li>values-prod.yaml</li>
    <li>README.md</li>
    <li>Helm templates for all detected resources</li>
    <li>.helmignore configuration</li>
</ul>

<h2>Validation Engine</h2>

<p>
The integrated validation engine scans Kubernetes resources and identifies potential issues including missing probes, absent resource limits, invalid service selectors, orphaned services, and deployment configuration risks. Findings are categorized as warnings or errors and contribute to an overall production readiness score.
</p>

<h2>Benefits</h2>

<ul>
    <li>Reduces manual Helm chart creation effort</li>
    <li>Improves deployment consistency</li>
    <li>Accelerates Kubernetes migration projects</li>
    <li>Promotes Helm best practices</li>
    <li>Simplifies environment-specific deployments</li>
    <li>Enhances DevOps productivity</li>
    <li>Provides immediate deployment validation feedback</li>
</ul>

<h2>Technology Stack</h2>

<ul>
    <li>HTML5</li>
    <li>CSS3</li>
    <li>Vanilla JavaScript</li>
    <li>js-yaml Parser</li>
    <li>JSZip Export Engine</li>
    <li>Prism Syntax Highlighter</li>
</ul>

<h2>Conclusion</h2>

<p>
The Kubernetes YAML to Helm Chart Generator provides a fast, reliable, and user-friendly solution for converting Kubernetes manifests into maintainable Helm charts. By combining automated template generation, validation, visualization, and export capabilities within a single browser application, the tool streamlines cloud-native deployment workflows and improves operational efficiency.
</p>
