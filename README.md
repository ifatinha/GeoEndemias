# GeoEndemias

Sistema para gerenciamento e georreferenciamento das visitas realizadas por Agentes de Combate às Endemias (ACE).

## Objetivo

O GeoEndemias tem como objetivo facilitar o trabalho em campo dos Agentes de Combate às Endemias por meio de um mapa interativo da microárea, permitindo o registro das visitas diretamente sobre os imóveis.

Além do registro das visitas, o sistema busca fornecer uma visão clara da situação da microárea, auxiliando no planejamento das ações e na geração de indicadores.

## Funcionalidades previstas

### Cadastro

- Agentes
- Microáreas
- Quadras
- Imóveis

### Visitas

- Registro de visitas
- Geolocalização automática
- Data e hora da visita
- Situação do imóvel
- Registro de focos
- Tratamento realizado
- Observações
- Fotografias

### Mapa

- Visualização da microárea
- Identificação dos imóveis visitados
- Diferenciação por cores conforme a situação da visita
- Navegação por quadras
- Localização do agente em tempo real

### Relatórios

- Quantidade de imóveis visitados
- Imóveis fechados
- Recusas
- Pendências
- Índices por microárea
- Histórico de visitas

## Tecnologias (planejamento inicial)

### Front-end

- React
- Leaflet
- TypeScript

### Back-end

- FastAPI (Python)

### Banco de Dados

- PostgreSQL
- PostGIS

### Mapas

- OpenStreetMap

## Estrutura prevista

```
GeoEndemias/

├── frontend/
├── backend/
├── database/
├── docs/
├── assets/
└── README.md
```

## Roadmap

### Fase 1

- [ ] Criar estrutura do projeto
- [ ] Sistema de autenticação
- [ ] Cadastro de agentes
- [ ] Cadastro das microáreas

### Fase 2

- [ ] Cadastro dos imóveis
- [ ] Visualização no mapa
- [ ] Registro das visitas

### Fase 3

- [ ] Dashboard
- [ ] Estatísticas
- [ ] Relatórios

### Fase 4

- [ ] Funcionamento offline
- [ ] Sincronização automática
- [ ] Aplicativo PWA

## Licença

Este projeto está licenciado sob a licença MIT.
