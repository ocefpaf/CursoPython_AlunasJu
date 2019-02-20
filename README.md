# Curso básico de matplotlib e outras ferramentas para gráficos em Python

## Instalação

1. Navegue até http://conda.pydata.org/miniconda.html e faça download da versão apropriada para o seu sistema (99.99% de chance do seu Windows ser 64bits);
2. Siga o "default" para a instalação;
3. Faça download do arquivo [environment.yml](https://raw.githubusercontent.com/ocefpaf/CursoPython_AlunasJu/master/environment.yml)
4. Abra um terminal onde baixou o arquivo e digite:

```shell
conda config --add channels conda-forge --force
conda update --yes --all
conda config --set channel_priority strict
conda env create --quiet --file environment.yml
```

Para testar tente entrar no ambiente instalado com o comando:

```
conda activate LabJu
jupyter notebook
```

Isso deve "acionar" o ambiente e abrir o notebook no seu browser padrão.


## Binder

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ocefpaf/CursoPython_AlunasJu/master)
