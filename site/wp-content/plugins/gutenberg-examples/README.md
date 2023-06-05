# Gutenberg Examples

Bloco simples de exemplo.

## Configurações iniciais para construir o build do bloco

### 1 - Instalar as dependencias

```bash
npm install
```

### 2 - Executar o primeiro build

```bash
npm run build
```

## Ativar o plugin no wordpress

Gutenberg Examples are distributed as WordPress plugin.

1. Navigate to the **Plugins > Plugins instalados** screen in your WordPress administrative dashboard.
2. Ative o plugin **Gutenberg Examples**
3. You’re done!

## Adicionando o bloco na página de exemplo

1. Navigate to the **Páginas > Plugins instalados** screen in your WordPress administrative dashboard.
2. Edit **Página de exemplo**
3. Adicione o bloco: **Example: Basic (ESNext)**
4. Congratulations, the custom block has been added to your page!

## Desenvolvimento

O código fonte do bloco está em: **./01-basic-esnext/**
A cada modificação no código do bloco, execute o comando abaixo, para executar o novo build:

```bash
npm run build
```
