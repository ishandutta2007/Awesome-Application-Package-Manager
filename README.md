# Awesome-Application-Package-Manager

# Awesome-Application-Package-Manager 📦 🚀

<p align="center">
  <img src="assets/banner.svg" alt="Awesome Application Package Manager Banner" width="100%">
</p>

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a>
  <a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Application-Package-Manager"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Application-Package-Manager?style=social" alt="GitHub_Stars"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Application-Package-Manager/fork"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Application-Package-Manager?style=social" alt="GitHub Forks"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Application-Package-Manager/blob/main/LICENSE"><img src="https://img.shields.io/github/license/ishandutta2007/Awesome-Application-Package-Manager?color=blue" alt="License"/></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

---

## 🌟 Top Application Package Manager Ecosystem

**Curated List of Commercial Package Registries & Open-Source Artifact Management Systems**  
*Focused on Dependency Resolution, Universal Artifact Storage, Supply Chain Security, Package Registries & Self-Hosted Repository Managers*

**Last updated: October 2026** 📅

---

### 📌 Overview & SEO Summary
Welcome to the ultimate curated directory of **application package managers**, **universal artifact repositories**, and **language-specific package registries**. Whether you are looking for enterprise-grade commercial solutions (such as *JFrog Artifactory*, *Cloudsmith*, and *Sonatype Nexus*), or self-hostable open-source alternatives (like *Reposilite*, *Verdaccio*, and *Pulp*), this list covers category leaders, dependency resolution, and privacy-respecting artifact management.

**Key Market Context:**
- **Salesforce is fully shifting development from first-generation packaging (1GP) to second-generation managed packaging (2GP)** — 2GP is the **only packaging technology Salesforce is investing in**, with a CLI-based development model [citation:1].
- **PyPI served 2.56 trillion requests and transferred 1.92 exabytes of data in 2025** — an average of **81,000 requests per second** — while processing **more than 2,000 malware reports** with **66% handled within 4 hours** [citation:4].
- **Homebrew 5.0.0** enables **parallel downloads by default**, promotes **Linux ARM64 to Tier 1 support**, and will **disable casks that fail Gatekeeper checks** in September 2026 [citation:5].
- **CocoaPods transitioned to maintenance mode in August 2024** after 13 years — with **Swift Package Manager (SPM) as Apple's successor** — though it remains in use for React Native and Flutter [citation:6].
- **Maven Central is professionally managed by Sonatype** with **mandatory signing, namespace control, and metadata validation** — keeping it **remarkably free of supply chain attacks** seen in other ecosystems [citation:19].
- **JFrog Artifactory supports 60+ package technologies** — from Java, C, Rust to Docker, Helm, PyTorch, and TensorFlow — as a **universal artifact repository manager** [citation:9].

---

## 📑 Table of Contents
- [🏢 SaaS & Commercial Platforms](#-saas--commercial-platforms)
- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)
- [🛠️ How to Contribute](#%EF%B8%8F-how-to-contribute)
- [📊 Star History](#-star-history)
- [🤝 Support & Sponsorship](#-support--sponsorship)
- [⚠️ Disclaimer](#%EF%B8%8F-disclaimer)

---

## 🏢 SaaS / Commercial Platforms

The application package manager market spans **language-specific registries** (npm, PyPI, RubyGems, Maven Central) that serve **millions of developers with free public access**, **universal artifact repositories** (JFrog Artifactory, Cloudsmith, Sonatype Nexus) that provide **multi-format support with security and governance**, and **platform-native package managers** (Salesforce AppExchange, Homebrew, CocoaPods) that serve **specific ecosystems**. **Salesforce AppExchange** is **free for existing Salesforce customers** [citation:1]. **JFrog Artifactory** uses **custom enterprise pricing** with **60+ package technologies** supported [citation:9]. **Cloudsmith** uses **usage-based pricing** with **28+ formats supported** [citation:10].

| SaaS / Commercial Platform | Company / Owner | Valuation / Market Cap | Standard Edition Starting Price | Free Tier / Free Trial Limits | Description |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **[Salesforce AppExchange Package Manager](https://appexchange.salesforce.com/)** ☁️ | Salesforce | ~$250 Billion | **Free for existing Salesforce customers** | **Free: included with Salesforce subscription** | **Salesforce-native package manager** — **Second-generation managed packages (2GP) for AppExchange distribution and unlocked packages for internal apps** [citation:1]. **CLI-based development model** — the only packaging technology Salesforce is investing in. **Multilevel dependency resolution** with automatic transitive dependency calculation. **Download package metadata** for any specific package version. |
| **[JFrog Artifactory](https://jfrog.com/artifactory/)** 🐸 | JFrog | ~$5 Billion | **Custom enterprise pricing** | **Free trial available** | **Universal artifact repository manager** — **Supports 60+ package technologies** including Maven, npm, PyPI, Docker, Helm, PyTorch, and TensorFlow [citation:9]. **Full lifecycle management**: curation, creation, promotion, distribution, and archival. **Proxy and cache public repositories** to prevent latency and outage issues. **Single source of truth for all binaries**. |
| **[Cloudsmith](https://cloudsmith.com/)** 📦 | Cloudsmith | Private | **Usage-based pricing**; **free tier for open-source** | **Free tier for open-source projects** | **Universal artifact management platform** — **Supports 28+ formats with native tooling integrations** and registry upstreams to proxy and cache popular sources [citation:10]. **Package deny policies** for supply chain control. **Block until scan** guarantees all security checks complete before download. **Package promotion** between repositories via move or copy. |
| **[npm](https://www.npmjs.com/)** 📗 | npm (GitHub/Microsoft) | ~$3.90 Trillion (Microsoft) | **Free for public packages**; **private from $7/user/month** | **Free: unlimited public packages** | **The package manager for Node.js** — **Default registry at registry.npmjs.org** [citation:2]. **Local mode** installs packages into `./node_modules` and **global mode** installs into `$NPM_CONFIG_PREFIX/lib/node_modules`. **Extremely configurable** with 5 configuration sources. **The largest package registry in the world**. |
| **[PyPI](https://pypi.org/)** 🐍 | Python Software Foundation | N/A (Non-profit) | **Free for public packages** | **Free: unlimited public packages** | **The Python Package Index** — **2.56 trillion requests and 1.92 exabytes transferred in 2025** [citation:4]. **Trusted Publishing** adopted by **50,000+ projects** with **20%+ of uploads via trusted publishers**. **Attestations** supported by all Trusted Publishing providers — **17% of uploads included attestations**. **Enhanced 2FA** with **52% of active users using non-phishable 2FA**. |
| **[Maven Central](https://central.sonatype.com/)** ☕ | Sonatype | Private | **Free for public artifacts** | **Free: unlimited public artifacts** | **The largest Java repository** — **Professionally managed by Sonatype for nearly two decades** [citation:19]. **Mandatory signing** for all artifacts — no unsigned or unverifiable binaries. **Namespace control** — publishers must control a domain matching their groupId. **Metadata validation** ensures components meet formatting and policy standards. **Remarkably free of supply chain attacks**. |
| **[Homebrew](https://brew.sh/)** 🍺 | Homebrew | N/A (Open Source) | **Free** | **Free forever** | **The package manager for macOS and Linux** — **Version 5.0.0 enables parallel downloads by default** [citation:5]. **Linux ARM64/AArch64 promoted to Tier 1 support**. **Official macOS 26 (Tahoe) support**. **Casks without codesigning deprecated** — disabling in September 2026. **Homebrew Bundle** dumps and installs dependencies from Brewfile. |
| **[RubyGems](https://rubygems.org/)** 💎 | Ruby Central | N/A (Non-profit) | **Free for public gems** | **Free: unlimited public gems** | **The Ruby package manager** — **Built into Ruby since 1.9** [citation:18]. **`gem install`, `gem update`, `gem search`, `gem build`** commands. **Gem is the packaging format for Ruby libraries and applications**. **The standard for Ruby dependency management**. |
| **[CocoaPods](https://cocoapods.org/)** 🍫 | CocoaPods | N/A (Open Source) | **Free** | **Free forever** | **The dependency manager for Swift and Objective-C** — **103K+ libraries and 3M+ apps** [citation:6]. **Source-based distribution with automatic Xcode integration**. **Maintenance mode since August 2024** — **Swift Package Manager is Apple's successor**. **Still used by React Native and Flutter**. |
| **[Sonatype Nexus Repository](https://www.sonatype.com/products/nexus-repository)** 🔵 | Sonatype | Private | **Custom enterprise pricing** | **Free: Nexus OSS** | **Universal artifact repository** — **Proxy and cache Maven Central and other repositories** [citation:8]. **Supports Maven, npm, Docker, PyPI, and more**. **The original Maven repository manager**. |

---

## 🔓 Open-Source GitHub Projects

*Sorted by GitHub_Stars_Count (Descending)* 🌟

- **[Verdaccio](https://github.com/verdaccio/verdaccio)** [![Stars](https://img.shields.io/github/stars/verdaccio/verdaccio?style=social&color=white)](https://github.com/verdaccio/verdaccio/stargazers)  
  **A lightweight Node.js private proxy registry**, MIT licensed. **The leading open-source npm registry alternative** — **self-hosted private registry with proxy caching for npmjs.org** . **Plugin architecture for authentication, storage, and notifications** . **Docker deployment** . **The most widely deployed open-source npm registry**. 📗

- **[Reposilite](https://github.com/dzikoysk/reposilite)** [![Stars](https://img.shields.io/github/stars/dzikoysk/reposilite?style=social&color=white)](https://github.com/dzikoysk/reposilite/stargazers)  
  **Lightweight and easy-to-use repository management software dedicated for Maven-based artifacts**, Apache-2.0 licensed. **Self-hosted solution that replaces Nexus, Archiva, or Artifactory with reduced resource consumption** . **Runs with just 20MB of RAM and Java 11+** . **Docker and Helm chart deployment** . **Backend: Kotlin + Javalin + Exposed; Frontend: Vue3 + Vite + WindiCSS** . **The most lightweight open-source Maven repository manager** [citation:12]. ☕

- **[Pulp](https://github.com/pulp/pulp)** [![Stars](https://img.shields.io/github/stars/pulp/pulp?style=social&color=white)](https://github.com/pulp/pulp/stargazers)  
  **A platform for managing repositories of content and pushing that content out to large numbers of consumers**, GPL-2.0 licensed. **The most flexible open-source artifact management platform** — **supports RPM, Debian, PyPI, npm, Maven, and more** . **Plugin architecture for custom content types** . **REST API for automation** . **The standard for Linux repository management**. 🐧

- **[Apache Archiva](https://github.com/apache/archiva)** [![Stars](https://img.shields.io/github/stars/apache/archiva?style=social&color=white)](https://github.com/apache/archiva/stargazers)  
  **The Build Artifact Repository Manager**, Apache-2.0 licensed. **The original open-source Maven repository manager** — **proxy, cache, and host Maven artifacts** . **Web UI for browsing and administration** . **The foundational open-source Maven repository**. 🏛️

- **[Nexus Repository OSS](https://github.com/sonatype/nexus-public)** [![Stars](https://img.shields.io/github/stars/sonatype/nexus-public?style=social&color=white)](https://github.com/sonatype/nexus-public/stargazers)  
  **The world's most widely used repository manager**, Eclipse Public License. **The most widely deployed open-source artifact repository** — **supports Maven, npm, Docker, PyPI, and more** . **Proxy and cache public repositories** to prevent latency and outage issues [citation:8]. **The standard for enterprise artifact management**. 🔵

- **[Artipie](https://github.com/artipie/artipie)** [![Stars](https://img.shields.io/github/stars/artipie/artipie?style=social&color=white)](https://github.com/artipie/artipie/stargazers)  
  **Binary Artifact Management Tool**, MIT licensed. **A modern, open-source artifact management platform** — **supports Maven, npm, Docker, PyPI, and more** . **YAML-based configuration** . **Docker deployment** . **The modern alternative to Nexus and Artifactory**. 🛠️

- **[webman](https://github.com/candrewlee14/webman)** [![Stars](https://img.shields.io/github/stars/candrewlee14/webman?style=social&color=white)](https://github.com/candrewlee14/webman/stargazers)  
  **A cross-platform package manager for the web**, MIT licensed. **No elevated permissions required** — **add, remove, and manage web-distributed software binaries** . **Package recipes are simple YAML files** . **Windows, Linux, and MacOS supported** . **All resources in `~/.webman`** — remove the directory and everything is uninstalled . **The most accessible cross-platform package manager for web binaries** [citation:11]. 🌐

- **[Homebrew Bundle](https://github.com/Homebrew/homebrew-bundle)** [![Stars](https://img.shields.io/github/stars/Homebrew/homebrew-bundle?style=social&color=white)](https://github.com/Homebrew/homebrew-bundle/stargazers)  
  **Bundler for Homebrew, Homebrew Cask, and the Mac App Store**, BSD-2-Clause licensed. **Dumps and installs dependencies from a Brewfile** . **Supports VSCode extensions, Cargo packages, uv tools, Flatpak, Winget, and Krew plugins** [citation:16]. **The standard for reproducible Homebrew environments**. 🍺

- **[FPM](https://github.com/jordansissel/fpm)** [![Stars](https://img.shields.io/github/stars/jordansissel/fpm?style=social&color=white)](https://github.com/jordansissel/fpm/stargazers)  
  **Effing package management! Build packages for multiple platforms with great ease and sanity**, MIT licensed. **Convert between package formats** — **deb, rpm, gem, npm, and more** . **The Swiss Army knife of package conversion** . **The standard for building packages for multiple platforms**. 🔧

- **[Chocolatey](https://github.com/chocolatey/choco)** [![Stars](https://img.shields.io/github/stars/chocolatey/choco?style=social&color=white)](https://github.com/chocolatey/choco/stargazers)  
  **The package manager for Windows**, Apache-2.0 licensed. **The most widely used Windows package manager** — **software management automation with PowerShell** . **Chocolatey Community Repository for public packages** . **The standard for Windows package management**. 🍫

- **[Scoop](https://github.com/ScoopInstaller/Scoop)** [![Stars](https://img.shields.io/github/stars/ScoopInstaller/Scoop?style=social&color=white)](https://github.com/ScoopInstaller/Scoop/stargazers)  
  **A command-line installer for Windows**, Unlicense. **The developer-friendly Windows package manager** — **installs from the command line without admin rights** . **Git and GitHub-based package definitions** . **The most accessible Windows package manager for developers**. 🥄

- **[Pixi](https://github.com/prefix-dev/pixi)** [![Stars](https://img.shields.io/github/stars/prefix-dev/pixi?style=social&color=white)](https://github.com/prefix-dev/pixi/stargazers)  
  **A fast, modern and reproducible package management tool**, BSD-3-Clause licensed. **Supports both PyPI and Conda packages** — **flexibility in sourcing dependencies** . **Multi-language dependency management** (Python with Rust, C/C++) . **Reproducibility guaranteed through `pixi.lock`** . **The most modern Python package manager** [citation:15]. 🐍

---

## 🛠️ How to Contribute

Contributions are welcome! Follow these steps to submit new package manager platforms or open-source artifact management software:

1. 🍴 **Fork** the repository.
2. 📝 **Add/edit** entries in `README.md` maintaining table/list structure and formatting.
3. 🔗 Include project title, official website/GitHub link, exact Stars_Count, license, and brief description.
4. 🚀 Submit a **Pull Request** with a descriptive summary of your changes.

---

## 📊 Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-Application-Package-Manager&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-Application-Package-Manager&type=date&legend=top-left)

---

## 🤝 Support & Sponsorship

If you find this application package manager repository useful, please consider supporting the project:

- ⭐ **Star** this repository to increase visibility!
- 🔀 **Fork** and share with fellow developers, DevOps engineers, and open-source advocates.
- ☕ **Sponsor & Buy Me a Coffee**: Support ongoing open-source curation via the [GitHub Sponsor Dashboard](https://github.com/sponsors/ishandutta2007).

---

## ⚠️ Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement. ℹ️
- **Salesforce is fully shifting from 1GP to 2GP** — **2GP is the only packaging technology Salesforce is investing in** [citation:1]. **CocoaPods is in maintenance mode** — **Swift Package Manager is Apple's successor** [citation:6]. **Homebrew will disable casks that fail Gatekeeper checks in September 2026** [citation:5].
- **PyPI security is improving but threats remain** — **66% of malware reports handled within 4 hours** and **92% within 24 hours** [citation:4]. **Trusted Publishing adopted by 50,000+ projects** and **attestations supported by all providers**. **Always verify package integrity and provenance**.
- **Open-source artifact repositories are not turnkey** — **Reposilite requires only 20MB RAM and Java 11+** [citation:12]. **Verdaccio requires Node.js and Docker** . **Pulp requires Python and PostgreSQL** . **Always validate package resolution, caching, and security policies with a proof-of-concept** before production deployment. 📦

---

<p align="center">
  <b>Made with ❤️ for developers, DevOps engineers, and open-source package management advocates.</b>
</p>
