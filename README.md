<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com/?lines=%24+ansible-playbook+site.yml;%24+terraform+apply+-auto-approve;%24+docker+compose+up+-d;%24+kubectl+get+pods&center=true&vCenter=true&font=Fira+Code&size=18&color=22C55E&width=520&height=40&duration=3000&pause=1000)](https://github.com/meryambej)

<img src="images/terminal.svg" width="820" alt="Animated terminal: neofetch shows Meryam, IT Architecture and Cloud Computing Engineer, focused on DevOps, Linux and Cloud, open to relocation in France">

![Location](https://img.shields.io/badge/Based_in-France-0f172a?style=for-the-badge)
![Focus](https://img.shields.io/badge/Focus-DevOps_·_Linux_·_Cloud-2563eb?style=for-the-badge)
![Status](https://img.shields.io/badge/Open_to-Relocation-22c55e?style=for-the-badge)

</div>

<!-- Add your links here, then uncomment:
<div align="center">
🌐 Portfolio: https://your-portfolio-url · 💼 LinkedIn: https://www.linkedin.com/in/your-handle
</div>
-->

<div align="center">

<img src="images/stack.svg" width="820" alt="Tech stack. Cloud and DevOps: Linux, Ubuntu, AlmaLinux, Kali, Bash, Ansible, Terraform, Docker, Kubernetes, Azure, AWS, OpenStack, Grafana, Prometheus, KVM. Backend: Python, Java, C#, .NET, Spring, C. Frontend: Angular, React, TypeScript, JavaScript, HTML, CSS. Databases: MySQL, MariaDB, Oracle. Tools: Git, GitHub, GitLab, Postman, Swagger, Figma, UML.">

</div>

## `$ ./deploy.sh`

A Flask app deployed end to end by a CI/CD pipeline I built: every push builds a Docker image, publishes it, and redeploys the container on AWS EC2 through a self-hosted GitHub Actions runner.

```mermaid
flowchart LR
    A([git push]) --> B[GitHub Actions<br/>self-hosted runner]
    B --> C[docker build]
    C --> D[(Docker Hub)]
    D --> E[AWS EC2<br/>stop old, run new]
    E --> F([live])

    classDef step fill:#bbf7d0,stroke:#16a34a,stroke-width:2px,color:#052e16
    classDef edge fill:#86efac,stroke:#15803d,stroke-width:2px,color:#052e16
    class B,C,D,E step
    class A,F edge
    linkStyle default stroke:#22c55e,stroke-width:2px
```

<!-- Link the repo: [View the project](https://github.com/meryambej/your-repo) -->

## `$ cat stats`

![My GitHub Statistics](images/userstats.svg)