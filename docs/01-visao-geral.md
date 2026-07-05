# Casa360-IA - Visão Geral

## 🏠 O Que É?

**Casa360-IA** é um aplicativo inteligente que funciona como um **Mecânico Virtual da Casa**, disponível em mobile (Flutter) e web (Next.js). Utiliza IA e visão computacional para ajudar moradores a:

- ✅ Diagnosticar problemas em sistemas residenciais via câmera + IA
- ✅ Tirar dúvidas através de uma base de conhecimento estruturada
- ✅ Receber orientações passo a passo para resolvê-los
- ✅ Gerenciar o histórico de manutenções e diagnósticos

## 🎯 Objetivo Principal

Empoderar moradores residenciais com conhecimento técnico instantâneo, reduzindo chamados desnecessários de técnicos e economizando tempo e dinheiro.

## 🚀 MVP - Fase 1

### Funcionalidades Core:

#### 1. **Câmera + IA para Diagnóstico**
- Tirar foto do problema
- IA (Google Vision + Gemini) analisa e identifica o issue
- Retorna: tipo de problema, severidade, solução recomendada

#### 2. **Base de Conhecimento Inteligente**
- FAQ estruturado por área (elétrica, hidráulica, aquecimento, eletrodomésticos)
- Busca semântica inteligente
- Artigos com passo a passo detalhado
- Links para vídeos tutoriais

#### 3. **Chat Diagnóstico com IA**
- Conversa interativa para refinar o diagnóstico
- Histórico de conversas salvo
- Recomendações personalizadas

#### 4. **Histórico e Gestão**
- Guardar diagnósticos realizados
- Comparar evoluções de problemas
- Exportar relatórios em PDF

## 📊 Arquitetura de Alto Nível

```
┌──────────────────────────────────────────────────┐
│    Frontend (Mobile + Web)                       │
│  Flutter (iOS/Android) + Next.js (Web)          │
└──────────────────────────────────┬───────────────┘
              ↓
┌──────────────────────────────────────────────────┐
│    API Backend (Firebase)                        │
│  • Cloud Functions (Node.js)                     │
│  • Firestore (Dados)                             │
│  • Storage (Imagens)                             │
└──────────────────────────────────┬───────────────┘
              ↓
┌──────────────────────────────────────────────────┐
│    Inteligência Artificial                       │
│  • Google Vision API                             │
│  • Google Gemini API                             │
└──────────────────────────────────────────────────┘
```

## 🗄️ Stack Tecnológico

| Camada | Tecnologia |
|--------|-----------|
| **Frontend Mobile** | Flutter 3.x |
| **Frontend Web** | Next.js 14 + React 18 + TailwindCSS |
| **Backend** | Firebase |
| **IA - Visão** | Google Vision API |
| **IA - Linguagem** | Google Gemini API |

## 📈 Fases do Projeto

### Fase 1: MVP (Atual)
- Câmera + diagnóstico via IA
- Base de conhecimento
- Chat com IA
- Histórico de diagnósticos

### Fase 2: Expansão
- Agendamento de técnicos
- Sistema de ratings
- Notificações push

### Fase 3: Enterprise
- Painel administrativo
- Analytics
- Integração com IoT

## 👥 Público-Alvo

- **Idade**: 25-65 anos
- **Local**: Residências urbanas e suburbanas
- **Necessidade**: Diagnosticar e resolver problemas residenciais

---

**Status**: 🟢 Projeto Iniciado  
**Data**: 2026-07-05