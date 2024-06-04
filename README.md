<p align="center">
    <a href="https://toitzi.dev" target="_blank">
        <!--suppress CheckImageSize -->
        <img src="./logo.png" width="100" height="100" alt="Logo">
    </a>
</p>

<p align="center">
    docker-compose file for kimai
</p>

<p align="center">
<img alt="GitHub License" src="https://img.shields.io/github/license/toitzi/kimai-docker">
<img alt="GitHub Sponsors" src="https://img.shields.io/github/sponsors/toitzi">
<img alt="GitHub Issues" src="https://img.shields.io/github/issues/toitzi/kimai-docker">
</p>

## Getting Started

This repository contains a `docker-compose` file for [Kimai](https://www.kimai.org/).

### Prerequisites

- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/install/)
- [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

### Installation

1. Clone the repository:

```bash
git clone https://github.com/toitzi/kimai-docker.git
```

2. Change into the directory:

```bash
cd kimai-docker
```

3. Copy the `.env.example` file to `.env` and adjust the values as needed:

```bash
cp .env.example .env
```

4. Start the containers:

```bash
docker-compose up -d
```

## License

The repository is open-sourced software licensed under the [MIT license](LICENSE.md).
