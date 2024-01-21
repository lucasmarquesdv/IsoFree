# IsoFree (ISOS, VDIS e entre outros)

![GitHub repo size](https://img.shields.io/github/repo-size/lucasmarquesdv/README-template?style=for-the-badge)
![GitHub language count](https://img.shields.io/github/languages/count/lucasmarquesdv/README-template?style=for-the-badge)
![GitHub forks](https://img.shields.io/github/forks/lucasmarquesdv/README-template?style=for-the-badge)
![Bitbucket open issues](https://img.shields.io/bitbucket/issues/lucasmarquesdv/README-template?style=for-the-badge)
![Bitbucket open pull requests](https://img.shields.io/bitbucket/pr-raw/lucasmarquesdv/README-template?style=for-the-badge)
<div align="center">
<img src="https://media.giphy.com/media/l1J9qemh1La8b0Rag/giphy.gif" alt="Gif">
</div>
> Este diretório foi criado com o intuito de servir como banco de dados de ISO's para VM's. Este diretório também tem o intuito de servir de backup.

### Ajustes e melhorias

O projeto ainda está em desenvolvimento e as próximas atualizações serão voltadas nas seguintes tarefas:

- [x] Kali Linux
- [ ] Metasploitable - EM BREVE
- [ ] WinXP - EM BREVE
- [ ] OpenSUSE Tumbleweed - EM BREVE

## 💻 Pré-requisitos

Antes de começar, verifique se você atendeu aos seguintes requisitos:

- Você instalou a versão mais recente do `<Oracle Virtual Box>`
- Você tem uma máquina `<Windows / Linux / MacOS>`. Indique qual sistema operacional é compatível / não compatível.
- Recomendo que leiam a documentação oficial da [Oracle](https://www.virtualbox.org/wiki/Documentation).

## 🚀 Instalando o VirtualBox

Para instalar o <VirtualBox>, siga estas etapas:

Oracle Linux:

```
yum install VirtualBox-6-1
```

Debian baseado nas distribuições Linux:

```
deb [arch=amd64 signed-by=/usr/share/keyrings/oracle-virtualbox-2016.gpg] https://download.virtualbox.org/virtualbox/debian <mydist> contrib
```

Lembre-se de mudar `mydist` pelo nome da sua distro. Exemplo: Bullseye, buster ou stretch, para distros Debian. jammy, eoan, bionic e xenial para distros Ubuntu.

As chaves de verificação da Oracle estão nestes repositórios a seguir:

```
sudo gpg --yes --output /usr/share/keyrings/oracle-virtualbox-2016.gpg --dearmor oracle_vbox_2016.asc
```

Combine o download e a registração:

```
wget -0- https://www.virtualbox.org/download/oracle_vbox_2016.asc | sudo gpg --yes --output /usr/share/keyrings/oracle-virtualbox-2016.gpg --dearmor
```

A chave de acesso para oracle_vbox_2016.asc é

```
B9F8 D658 297A F3EF C18D  5CDF A2F6 83C5 2980 AECF
Oracle Corporation (VirtualBox archive signing key) <info@virtualbox.org>
```

Para instalar o VirtualBox faça

```
sudo apt-get update
sudo apt-get install virtualbox-6.1
```

## ☕ Usando o VirtualBox

Para usar <VirtualBox>, você precisará das imagens. Este repositório é totalmente voltado para fins educativos.


## 📫 Contribuindo para o nosso reposítório

Para contribuir com <IsosFree>, siga estas etapas:

1. Bifurque este repositório.
2. Crie um branch: `git checkout -b <nome_branch>`.
3. Faça suas alterações e confirme-as: `git commit -m '<mensagem_commit>'`
4. Envie para o branch original: `git push origin <nome_do_projeto> / <local>`
5. Crie a solicitação de pull.

Como alternativa, consulte a documentação do GitHub em [como criar uma solicitação pull](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request).

## 🤝 Colaboradores

Agradecemos às seguintes pessoas que contribuíram para este projeto:

<table>
  <tr>
    <td align="center">
      <a href="https://avatars.githubusercontent.com/u/104745874?v=4" title="Lucas Marques">
        <img src="https://avatars.githubusercontent.com/u/104745874?v=4" width="100px;" alt="Foto do Contribuidor Lucas Marques"/><br>
        <sub>
          <b>Lucas Marques (RootmannWright)</b>
        </sub>
      </a>
    </td>
  </tr>
</table>

## 😄 Seja um dos contribuidores

Quer fazer parte desse projeto? Clique [Aqui](CONTRIBUTING.md) e leia como contribuir.

## 📝 Licença

Esse projeto está sob licença. Veja o arquivo [Licença](LICENSE.md) para mais detalhes.