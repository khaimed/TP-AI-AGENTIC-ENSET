# TP LLM et LangChain

Depot unique regroupant deux TPs du meme module.

## Structure

- [tp-langchain-agents](./tp-langchain-agents) : TP `Agents avec LangChain`
- [tp-prompt-engineering](./tp-prompt-engineering) : TP `Ingenierie des prompts`

## 1. TP Agents avec LangChain

Ce dossier contient un agent `chef personnel` construit avec :
- un `system message`
- une `memoire`
- un `tool` de recherche web
- un modele local via `Ollama`

Fichier principal :
- [chef_personnel_agent.py](./tp-langchain-agents/chef_personnel_agent.py)

Execution rapide :

```bash
cd tp-langchain-agents
pip install -r requirements.txt
python chef_personnel_agent.py
```

## 2. TP Ingenierie des prompts

Ce dossier contient les exercices du document sur :
- la tokenisation avec `tiktoken`
- les prompts avec `Ollama`
- les prompts avec `Groq`
- les prompts avec `OpenAI`
- une sortie JSON
- la generation et la description d'image

Projet principal :
- [README du TP Prompt](./tp-prompt-engineering/README.md)

Execution rapide :

```bash
cd tp-prompt-engineering
uv venv
uv sync
```

## Remarques

- Certains scripts demandent des cles API (`OpenAI`, `Groq`) ou un serveur `Ollama` actif.
- Les fichiers `.env` ne doivent pas etre pushes sur GitHub.
