<p align="center">
  <a href="" rel="noopener">
 <img width=200px height=200px src="https://avatars.githubusercontent.com/u/28861843?s=200&v=4" alt="Project logo"></a>
</p>

<h1 align="center">Katalon JFrog</h1>

<div align="center">

[![Status](https://img.shields.io/badge/status-active-success.svg)]()
[![GitHub Issues](https://img.shields.io/github/issues/kylelobo/The-Documentation-Compendium.svg)](https://github.com/kylelobo/The-Documentation-Compendium/issues)
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr/kylelobo/The-Documentation-Compendium.svg)](https://github.com/kylelobo/The-Documentation-Compendium/pulls)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)

</div>

---

<p align="center"> This is a sample project of using JFrog dependency manager.
    <br> 
</p>

## 📝 Table of Contents

- [Prerequisites](#prerequisites)
- [Deployment](#installing)

### Prerequisites <a name = "prerequisites"></a>

- Gradle 4.x.x - 6.x.x

### Installing <a name = "installing"></a>

1. Add your artifactory credential to `gradle.properties` file.

2. Resolve all denpendencies and copy them into `Drivers` folder. 
> Due to the way Java loading libraries, please close all Katalon Studio applications before execute the following command, and re-open it after the command has been completed.

```shell
$ gradle katalonCopyDependencies
```
