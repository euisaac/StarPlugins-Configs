# Configs — StarPlugins

Arquivos de configuração **padrão** dos plugins da [StarPlugins](https://starplugins.com.br),
como eles vêm de fábrica dentro de cada jar.

Serve para consultar o que mudou de uma versão para outra, comparar com a sua
configuração antes de atualizar e ver as opções disponíveis sem precisar abrir
o plugin no servidor.

> Estes são os arquivos **padrão**. A configuração que vale é a que está no seu
> servidor, em `plugins/<Plugin>/`. Copiar um arquivo daqui por cima do seu
> substitui tudo que você personalizou.

## Pastas

| Pasta | O que é |
|---|---|
| `StarLobby/` | Plugin de lobby (servidor Spigot/Paper) |
| `StarLobbyProxy/` | Módulo do StarLobby para o proxy Velocity |
| `StarPlugins/` | Loader que instala e atualiza os plugins |

## Como atualizar sua config sem perder o que você mexeu

O loader avisa no console quando o jar tem uma chave que o seu arquivo ainda
não tem, e o `/starplugins menu` mostra a lista. Na maioria dos casos dá para
completar por lá, sem mexer no arquivo à mão.
