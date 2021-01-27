# Coletânea Colaborativa

* [Diagrama C4 do sistema](#Diagrama-C4-do-sistema)
  * [Sistema de Coletânea Colaborativa](#Sistema-de-Colet%C3%A2nea-Colaborativa)
    * [API](#API)
    * [Aplicação de Página Única (SPA)](#Aplica%C3%A7%C3%A3o-de-P%C3%A1gina-%C3%9Anica-(SPA))
    * [Banco de Dados](#Banco-de-Dados)

---

## Diagrama C4 do sistema

**Nível 1: Diagrama de contexto**

A Coletânea Colaborativa está inserida em um contexto livre, sem qualquer dependência externa.

Os usuários considerados são 3, com suas respectivas funções de Colaborador, Revisor e Administrador.


![diagram](https://www.plantuml.com/plantuml/svg/0/PPB1ZjCm48RlbVeEfXUwqhQvSEAqgsu5I5rObLQ8KpLhJnjBjYUonw7mDWi7n0Fm17annaafHIlbuFns_l_x9xv9396pTqfJO3moZKSlRD0k6rGrSvDULrM4B_E3vJe_veInFnXuhibNOAA5qBhSv6hnQlRW8F3sVbKvO4miqcunsCuRoHYFngFLxUSFsytkqxlDszrg-MRv_cvwLVG7Z8d2L9ExLfC5ENYa28RYH5wtNkMKkwTeIJ2zqj20jWO4KHuj255fku-GL0CHL6q3fVdawkmQiHMRDROs3OvhJ0s5r3srw5H3KSMo9pPYSN82OxMb0AQuoWdzZmdJjO8cKWl1aAAiGlU3BlF0U0cvDTu6c_ZSOo7Stmho0IC6NR0fSwHqhfSKAk1S-f2doqpPY0D_7_JnQsBqqwJrC2xaxdj0K7ydnxQ54Yb0tZ9U1FJZGYz-Q2ptorDZx6baOSEUeeVkP_SRBqUgcjZzcXdSIorpcl3BWMItFFAqp6Mod7cmJgLUBWYR6iMHCGPmwjvgwKjxLikZhY4S1EFoWzvpF5gZ6wx2K72ReEX5xN_bCxKV-7_g3GRJNxa_)

## Sistema de Coletânea Colaborativa

`/Sistema de Coletânea Colaborativa`

[Diagrama C4 do sistema](#Colet%C3%A2nea-Colaborativa)

**Nível 2: Diagrama de containers**

A Coletânea Colaborativa consiste apenas de uma interface disponível aos usuários por meio de um SPA, usando uma API desenvolvida em [Strapi](https://strapi.io/) com banco de dados em MongoDB.


![diagram](https://www.plantuml.com/plantuml/svg/0/RLFDRXCn4Bv7oZkO750YXUJ2YLFRjA95QRlAZn2dQ6fF4oElPsLxjog85-7MSa3YpXFiYp7ZRKCZYA9eCplwVksZc22akdHAaqzWFOP-xvNrsjK6rIwbAhwRJWFSJROsxUgREcAGJVHfegcSWWaMVEFggfxEthuf7FYqlfnF7IICYKURsJFkf6AQVg_Vcnz_kbwlDXylLkUR-TdxiwlJuKZc1OP8VgZ9ZTLWHWvkA82XCE2_wrBLiMuVWYLMMYeD5MXhW4NoLxE8eBIz3H1L1G7KpdgAay5eZngmOPW5DZPsY0kC5VdOFZJeL4L11Nd7C0pnX0J6QaiUZA3oXlwh2UDOGHMe0Mz8KQry-uDUye4fcUJObDRRcFO-PgpxYqZUOa2lHJRLAL3SsuiA5QHQ_519BpdvHUZqPwBbVKnORawezWR2_J1gtUM6gNtq2EevmcGR68pKLyMVVaz-zvqCOmKYit9MG_kJFOYsedtOMW-g_Uvvh8RBudWauZz30v6phbBkO86W4ujQWNLtrXjPAJYIzfTAP421kgrz3j1rJULc3gnAgYNQp5gNoaE3Mx6Q3HugDJSCVm9UvsN6eoY4b-ItT78gZqjm3MJgA2LQVqkX55U_CN9oBWV1hqX5Az6nyoxYW2PtOQD0WyOOQTmTeJ5F4hYTz8r9_qSNL5OIB2wo16wwiY-2OBx349xE9oaEzS3--MfLBASVbjTNcQIZMQ3h2BBxEGE-LiWLO8FFIcGbjzW9MKSGUi6PPaZP-oPuifZlLjUvB8wwQRuR_qpp2JwOzdj7w4s-nNy0)

## API

`/Sistema de Coletânea Colaborativa/API`

[Diagrama C4 do sistema](#Colet%C3%A2nea-Colaborativa)

**Level 3: Component diagram**

Next you can zoom in and decompose each container further to identify the major structural building blocks and their interactions.

The Component diagram shows how a container is made up of a number of "components", what each of those components are, their responsibilities and the technology/implementation details.

**Scope**: A single container.

**Primary elements**: Components within the container in scope.
Supporting elements: Containers (within the software system in scope) plus people and software systems directly connected to the components.

**Intended audience**: Software architects and developers.

![diagram](https://www.plantuml.com/plantuml/svg/0/fLJBRjim4Bm7o3ziVIXim8qlFVKKsqcR17aOiTt7oLXHQvaj7m99sJMA_dkNb6B9QL04g2-cLgFPuUoGvpwW2vLMfoTlf16goWas8PJ-msZaS7TMoB2fiigJ4zO4Ck5CM3t2t4aqMrMLrMZw_jrCeGdBkzkHma0-S6arjRgq9kBBH7vwSZl-zh1ShBvSBwvMjvUVBkyl-eDOdp8lIaEkxqiSGcykJQ48PbWGZCjIIO51MjFZLzznYruuMGP0auCZ527MPyvkPKuUK2a86mB9KfsX01cQ7ym7wyg8o89AXZq42wBomMfo7hOIupVImOuoo9pTyMRFUeEkCXs5tTbCggGfzloA6fqqn-r1IIq3vU2hp7Dx6_v3ZgxxDNyvRQMWPxhoZDjVOC0CFKKfZwIm9eQdCip5XZJ6j_DW7SkCqsJp2kc3IsWMkBPEf_KGDkWtl0MiM8O9ZVqW7ENn4PKV0Wf1teEo1JzG44dMVEy3wTNbpz3NcO-6iSYrGqqmQVPTGpfIui3iEfaak70mg2C8CBDLQ1rAtMrb0gzOl_6OhEm8wJYqcZ0oHxVlOocvxNXsVHIg0VmwFG7-7VBQzx8mAOQ5WMi3aSfPfSX5sNUVf_384M_BiJfMYbEJVFLncf62jn2NBuxVrpOCdhTkDzORDqkOLvg3jd-LZaCGspZj-FnoBZspM6QflUPmHIa78_zMuabKZhCPZMYMxTiqlzB5dKm8Zu_0SR9TZ2DdANbYYdgoGn0Rh1zAz7vdNTuPth4E3j8Q1URqZpZ1nuHuGTKOwe-1JQf7eGySnxDeSXERyn5gCj0nOUdfu584j9FgAdoEQWdIGNqapE4jxBX4R4bKU7CncNQ_wB3LPoXHnkk6RzUhnM8sZ-ZVKMjg46_C9h1Fo9lvmtqBFQ0wsNePMMFrQmZrQ_ZEoUJfwly3)

## Aplicação de Página Única (SPA)

`/Sistema de Coletânea Colaborativa/Aplicação de Página Única (SPA)`

[Diagrama C4 do sistema](#Colet%C3%A2nea-Colaborativa)

**Level 3: Component diagram**

Next you can zoom in and decompose each container further to identify the major structural building blocks and their interactions.

The Component diagram shows how a container is made up of a number of "components", what each of those components are, their responsibilities and the technology/implementation details.

**Scope**: A single container.

**Primary elements**: Components within the container in scope.
Supporting elements: Containers (within the software system in scope) plus people and software systems directly connected to the components.

**Intended audience**: Software architects and developers.


![diagram](https://www.plantuml.com/plantuml/svg/0/RLBBRjD05Dr7yZzSiaga4czOmQPfg4XHsbfv2B6ABlQDFT9uPZIFH0Zn8-mG2oH-mp_6lNRJgXHlnlTrpZrpvZ94z36r6eB3RFHAcLAdYg29qOMtUUxnDAjLRDAN5CYNraGoSLRQDiVAApH7dLpA5szU5nfDtDskSesHGkJKVc5RPutqEoR8HjbeDVzylzlkFzrib_lLzOVhk_UJgUGNZ8lAa9-WKnSmdXStOpusqNCiVuMtn-uFO813CgMo1hMgiA803Zs2XKqn1sSzjAGiyFxBxRROv1ytztUpyNEA_PLDfaB_TSAAXSjfLMBtk_lL3nRTprePXEw7uJHC67WwdiAtR0JyFKgQU1inyFXQJbbnJLX6y3P5yX8lqLIQF0Ijk1-2Od2fAbFBHi_HM8iLj2iC95lqiQ2iR8bw4wt7cYI-fHAD2gs55BXda5ydzAnec0BEiW5Ih13mITti9IsM58BjQLWq7AnlcOJZRKEW-vmJuXU3Zln1QJ7cuRfuvo7tD2-JS6h84yG1hgOA659U4h0CE2ew0LyJKAKYD2hatCqTiWT6Tbc8lujxQzA3NSFxs0MKon1xyzxfmMFfEaiwtwYqJjyDjGVF_bSw2_gtbeqkoLJzy_qB)

## Banco de Dados

`/Sistema de Coletânea Colaborativa/Banco de Dados`

[Diagrama C4 do sistema](#Colet%C3%A2nea-Colaborativa)

**Level 3: Component diagram**

Next you can zoom in and decompose each container further to identify the major structural building blocks and their interactions.

The Component diagram shows how a container is made up of a number of "components", what each of those components are, their responsibilities and the technology/implementation details.

**Scope**: A single container.

**Primary elements**: Components within the container in scope.
Supporting elements: Containers (within the software system in scope) plus people and software systems directly connected to the components.

**Intended audience**: Software architects and developers.

![diagram](https://www.plantuml.com/plantuml/svg/0/fLHBRnen4BuZyH-c72gGQBZqr5Duf4sYF50WVPpGh7TOtFgnihrGLFM_T-mbx996LQHomPuTV_FDDvzzxWEwK6a56HfXPpJ3tFfkvuqqGbKvmIQ4qdyOZHpkpWePDbLMUNB2ca0cd0chHvWxYMQhgh8QJT-_coiquV7sPgGma0ySMasjBgs9-ILNwdQwdPlnj_l7vUhBrV9oTNFnwU9krX_4-9HnKHfoVL_Y47eBQGf5CCU2O5oMIWeCqfeUV_gEM_J2oJ80cXmSeGWnFdTsAtFoW4f1s118fkeCXTZX3yQ3TML4H44bmnw21L7vO3Kv3rk9yOnqiACCCcTttEnPRz1cfYEnMvj9bJZ5cbzHevFcj3megMMW77oLUIvlmt_GqNMzmrzEMode6Qyyu_8p39YXfqZbWHJMmF0KXeNOaCRuTH6iOvfncYnU8NrmAPi9hgtJQJs43VeDju0Lqp3X83y8HtdSel93G278Ur2su0q5aMWjzZwGNbty37sT-IWOarmxr0IJGzzrIejA79XT9v441uu2jGW1PhOAZKAfkgrCu1NpDnwJb2qYBOLM4yxCqUtxM4ekEvvVdPXg0B-w7U3VqQzzBmkJR5WOk38GePnLYboaVVjv2WziyIOSesEbs3L9Ln-d6I6uXRXySVo-bc7ml7JJM6zyMCAYqcoq_Qju78tOs6d7zvTzwHd5CagjDPihKZaA-JSJJw9oxCqen67PV4tpArtiP49uUWLEdUsY7TbBIHDJr9CTWjXWlIdH-vrrUMjufppOI6iKcDC_x0GVKyOBhCPG7mOMgHw5FcASpkBWcrYShz310oqH7ZqTLOe9pQJQ39zdDG3feZuGvl0MTXmYbYGol9vDfkqJBRJw3YN8-DpmwtgvNCuNCVjtv9eAn1VpODYdpEl5_LsJUingUUlbp3fNlmPGlmRld4oUdlu_)