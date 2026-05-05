# 🤖 Atividade #8 — LLM Agents com HuggingFace

> Agente inteligente capaz de raciocinar e usar ferramentas de forma autônoma,
> construído com a biblioteca **smolagents** do HuggingFace.

---

## 📌 Sobre o Projeto

Este projeto demonstra o funcionamento de um **LLM Agent** — um sistema onde
um modelo de linguagem age como "cérebro" que decide quais ferramentas usar
para resolver problemas, em vez de apenas gerar texto.

O agente criado é capaz de:
- 🔢 Resolver expressões matemáticas
- 📝 Contar palavras em um texto
- 🌡️ Converter temperaturas (Celsius → Fahrenheit)

---

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Função |
|---|---|
| `smolagents` | Framework de agentes do HuggingFace |
| `InferenceClientModel` | Acesso à API de modelos |
| `Qwen2.5-72B-Instruct` | Modelo LLM gratuito |
| `CodeAgent` | Tipo de agente que gera código Python |

---

## 🚀 Como Executar

1. Abra o arquivo `llm_agents_huggingface.ipynb` no [Google Colab](https://colab.research.google.com)
2. Crie seu token gratuito em [huggingface.co/settings/tokens](https://huggingface.co/settings/tokens)
3. Substitua `hf_SEU_TOKEN_AQUI` pelo seu token na célula indicada
4. Execute todas as células (**Runtime → Run all**)

---

## 📁 Arquivos
- ├── llm_agents_huggingface.ipynb   # Notebook com o código
- └── apresentacao_llm_agents.pdf    # Slides de apresentação

---

## 👩‍💻 Integrante

- Luana Ayumi Goto
- Maria Clara Ferreira Esteves

---

## 📚 Referências

- [smolagents – Documentação Oficial](https://huggingface.co/docs/smolagents)
- [HuggingFace – Plataforma de Modelos](https://huggingface.co)
- [Qwen2.5-72B-Instruct no HuggingFace](https://huggingface.co/Qwen/Qwen2.5-72B-Instruct)
- [Guia: Building Agents with smolagents](https://huggingface.co/blog/smolagents)
- [HuggingFace Inference API](https://huggingface.co/docs/api-inference)
