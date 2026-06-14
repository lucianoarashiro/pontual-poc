# Pontual — POC Navegável

> Proof of Concept do sistema de gestão de ponto e jornada Pontual.

## Fluxos disponíveis

| Fluxo | Arquivo | Perfil |
|---|---|---|
| Menu principal | `index.html` | — |
| App do colaborador | `mobile-home.html` | Colaborador |
| Marcação Bluetooth + Face ID | `mobile-faceid.html` | Colaborador |
| Fallback PIN | `mobile-pin.html` | Colaborador |
| Totem de ponto | `totem.html` | Todos |
| Interface RH | `desktop.html` | RH / Gestão |
| Gestão de dispositivos | `dispositivos.html` | Admin |
| Motor de políticas | `politica.html` | Admin |

## Deploy na Vercel

```bash
# 1. Clone o repositório
git clone https://github.com/seu-usuario/pontual-poc
cd pontual-poc

# 2. Deploy via Vercel CLI
npx vercel

# Ou conecte o repositório diretamente em vercel.com
```

## Estrutura

```
pontual-poc/
├── index.html          ← Menu de navegação
├── mobile-home.html    ← App colaborador
├── mobile-faceid.html  ← Fluxo Bluetooth + Face ID
├── mobile-pin.html     ← Fallback PIN
├── totem.html          ← Totem de ponto
├── desktop.html        ← Interface RH
├── dispositivos.html   ← Gestão de dispositivos
├── politica.html       ← Motor de políticas
└── vercel.json         ← Configuração Vercel
```

## Tecnologias

- HTML + CSS + JavaScript puro — sem dependências de build
- Tabler Icons via CDN
- Google Fonts via CDN
- Deploy estático — funciona em qualquer CDN

---

**Confidencial · Uso interno · Versão 0.2 · Junho 2025**
