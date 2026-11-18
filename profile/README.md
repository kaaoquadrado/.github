<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/k2-logo-tinta-clara.svg">
  <img src="./assets/k2-logo-tinta-escura.svg" alt="K²" width="150">
</picture>

### Tecnologia simples para quem serve pessoas.

Criamos sistemas de pedidos e pagamentos para **cantinas escolares** e **restauração**, com totem tátil, app e site, para acabar com filas, senhas em papel e contas feitas à mão.

![Lisboa, Portugal](https://img.shields.io/badge/📍_Lisboa-Portugal-FF5A36?style=flat-square&labelColor=14161C) ![Piloto](https://img.shields.io/badge/Piloto-janeiro_2027-FF5A36?style=flat-square&labelColor=14161C)

</div>

---

## 🍽️ KlikaAqui

O nosso primeiro produto. Nasceu como projeto de PAP numa escola profissional de Lisboa e está a crescer até ser um sistema completo para refeitórios e bares.

<table>
  <tr>
    <td width="50%" valign="top">
      <h4>🖥️ Totem</h4>
      Ecrã tátil à entrada do refeitório. O aluno entra, vê a ementa, reserva o almoço e recebe o talão com o PIN da refeição.
    </td>
    <td width="50%" valign="top">
      <h4>📱 App &amp; site</h4>
      Reservar a partir de casa, carregar saldo com <b>MB WAY</b> ou <b>Multibanco</b> e consultar o histórico.
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4>🧾 Painel da secretaria</h4>
      Gestão de contas, carregamentos ao balcão, ementas e notícias, tudo num só sítio.
    </td>
    <td width="50%" valign="top">
      <h4>🔒 Dinheiro bem guardado</h4>
      Cada cêntimo fica registado num histórico que não se apaga, e o saldo só muda no servidor.
    </td>
  </tr>
</table>

### Como funciona

```mermaid
flowchart LR
    T["🖥️ Totem"] --> API
    A["📱 App"] --> API
    S["🌐 Site"] --> API
    SEC["🧾 Secretaria"] --> API
    API(("⚙️ API K²")) --> DB[("🗄️ Base de dados<br/>(UE)")]
    API <--> PAG["💳 MB WAY / Multibanco"]
    API --> MAIL["✉️ E-mail"]
```

Todas as peças falam com uma única **API**. Assim, as regras do dinheiro vivem num só sítio e cada nova peça, seja um ecrã de cozinha ou um restaurante novo, liga-se sem mexer no resto.

## 🛠️ Com que trabalhamos

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white" alt="Django">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" alt="Flutter">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker">
</p>

## 🗺️ Onde estamos

- [x] Protótipo do totem (PAP)
- [x] Nova API com saldo seguro, reservas e carregamentos
- [ ] Totem no ecrã tátil novo + MB WAY real
- [ ] **Piloto numa escola de Lisboa**, janeiro 2027
- [ ] Mais escolas e os primeiros restaurantes

## 👋 Quem somos

O **K²** são dois irmãos, **Kaique** e **Kauã**: dois *K*, daí o quadrado. Somos programadores em Lisboa e estamos a construir o que gostávamos de ter tido na cantina da nossa escola.

<div align="center">

**Tens uma cantina, um bar ou um restaurante?** Fala connosco.

[![GitHub](https://img.shields.io/badge/Kaique-GitHub-14161C?style=for-the-badge&logo=github)](https://github.com/KakaAndrade2007) [![LinkedIn](https://img.shields.io/badge/Kaique-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/kaique-de-andrade)

<sub>Feito com ☕ em Lisboa · © 2026 K²</sub>

</div>
