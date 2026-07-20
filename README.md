<h1 align="center">Olá, eu sou o José Gabriel Pereira da Silva 👋</h1>
<h3 align="center">Desenvolvedor focado em Java e aplicações Full Stack 🚀</h3>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=2E9EF7&center=true&vCenter=true&width=600&lines=Java+Developer+%7C+Full+Stack;Hibernate+%2F+JPA+Enthusiast;Sempre+aprendendo+algo+novo!" alt="Typing SVG" />
</p>

---

### 💫 Sobre Mim

```yaml
desenvolvedor:
  foco: [Java, Full Stack]
  paixao: "transformar ideias em sistemas funcionais"
  filosofia: "código limpo > código rápido, mas gosto dos dois"
```

- 💻 Desenvolvedor focado em **Java** e aplicações **Full Stack**
- 🧠 Sempre estudando algo novo, sempre construindo algo útil
- 🤝 Aberto a colaborações e trocas de conhecimento

---

### 🔥 Principais Tecnologias

<p align="left">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=hibernate&logoColor=white" />
  <img src="https://img.shields.io/badge/JPA-007396?style=for-the-badge&logo=java&logoColor=white" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white" />
  <img src="https://img.shields.io/badge/WildFly-2B2B2B?style=for-the-badge&logo=wildfly&logoColor=white" />
  <img src="https://img.shields.io/badge/Apache_Tomcat-F8DC75?style=for-the-badge&logo=apachetomcat&logoColor=black" />
  <img src="https://img.shields.io/badge/Adobe_Flex-FF0000?style=for-the-badge&logo=adobe&logoColor=white" />
  <img src="https://img.shields.io/badge/BlazeDS-660066?style=for-the-badge&logo=adobe&logoColor=white" />
</p>

---

### 🧠 Atualmente Estudando

<p align="left">
  <img src="https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white" />
  <img src="https://img.shields.io/badge/Jakarta_EE-3572A5?style=flat-square&logo=eclipseide&logoColor=white" />
  <img src="https://img.shields.io/badge/Arquitetura_de_Software-4B32C3?style=flat-square" />
  <img src="https://img.shields.io/badge/APIs_REST-25D366?style=flat-square&logo=fastapi&logoColor=white" />
</p>

```mermaid
graph LR
    A[Java] --> B[Hibernate / JPA]
    B --> C[MySQL]
    C --> D[APIs REST]
    D --> E[Angular]
    E --> F[Jakarta EE]
    F --> G[Arquitetura de Software]
```

---

### 🚓 Projetos em Destaque

<table>
  <tr>
    <td width="33%">
      <h4>🚗 CadCollections</h4>
      <p>Sistema de gerenciamento de colecionadores e carros.</p>
      <p><code>Flex</code> · <code>Java</code> · <code>Hibernate</code></p>
    </td>
    <td width="33%">
      <h4>📦 CadProd</h4>
      <p>CRUD completo de produtos com persistência de dados.</p>
      <p><code>JPA</code> · <code>Hibernate</code> · <code>MySQL</code></p>
    </td>
    <td width="33%">
      <h4>🖥️ Swing-JPA</h4>
      <p>Sistema desktop com interface gráfica e banco de dados.</p>
      <p><code>Java Swing</code> · <code>Hibernate</code> · <code>MySQL</code></p>
    </td>
  </tr>
</table>

---

### 📊 Estatísticas do GitHub

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=josegabrielprgm&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=josegabrielprgm&layout=compact&theme=tokyonight&hide_border=true" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=josegabrielprgm&theme=tokyonight&hide_border=true" alt="GitHub Streak" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=josegabrielprgm&theme=tokyo-night&hide_border=true" alt="Activity Graph" />
</p>

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=josegabrielprgm&theme=tokyonight&no-frame=true&row=1&column=7" alt="GitHub Trophies" />
</p>

---

### 🏙️ GitHub City

<p align="center">
  <img src="https://raw.githubusercontent.com/josegabrielprgm/josegabrielprgm/main/profile-3d-contrib/profile-night-rainbow.svg" alt="GitHub 3D Contribution City" />
</p>

> ℹ️ Essa imagem é gerada automaticamente por uma **GitHub Action** rodando no seu próprio repositório `josegabrielprgm/josegabrielprgm`. Veja como configurar logo abaixo.

<details>
<summary>⚙️ Como ativar o GitHub City (clique para expandir)</summary>

1. No seu repositório especial `josegabrielprgm/josegabrielprgm`, crie o arquivo:
   `.github/workflows/profile-3d-contrib.yml`

2. Cole o conteúdo:

```yaml
name: GitHub 3D Contribution Calendar

on:
  schedule:
    - cron: "0 0 * * *" # roda todo dia à meia-noite
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
      - uses: yoshi389111/github-profile-3d-contrib@0.7.1
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
        with:
          username: josegabrielprgm
      - name: Commit & Push
        run: |
          git config user.name github-actions
          git config user.email github-actions@github.com
          git add -A .
          git commit -m "Atualiza GitHub City" || exit 0
          git push
```

3. Faça commit — a Action vai rodar automaticamente (ou clique em "Run workflow" manualmente pela aba **Actions**) e vai gerar os arquivos SVG dentro da pasta `profile-3d-contrib/`.

4. Temas disponíveis: troque `profile-night-rainbow.svg` por `profile-night-green.svg`, `profile-south.svg`, entre outros, conforme o que a Action gerar.

</details>

---

### ⚡ Fun Fact

```java
public class Dev {
    public static void main(String[] args) {
        boolean alive = true;
        while (alive) {
            code();
            learn();
            improve();
        }
    }
}
```

---

### 🌎 Conecte-se Comigo

<p align="left">
  <a href="mailto:josegabrielprgm@email.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://github.com/josegabrielprgm" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=josegabrielprgm&label=Profile%20Views&color=blue&style=flat" alt="Profile Views" />
</p>

<p align="center"><i>"while(alive) { code(); learn(); improve(); }"</i></p>
