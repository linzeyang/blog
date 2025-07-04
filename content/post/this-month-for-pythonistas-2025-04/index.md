+++
title = 'This Month for Pythonistas - April 2025'
description = "More MCP, A2A, Vibe Coding, Llama 4 and other fun stuff"
slug = "this-month-for-pythonistas-2025-04"
date = 2025-04-30T15:00:00+08:00
authors = ["Zeyang Lin"]
tags = ["python", "cli", "linux", "windows", "news"]
categories = ["python"]
series = ["this month for pythonistas"]
keywords = ["python", "pypi", "pycon", "linux", "github", "podcast", "AI", "LLM"]
image = "title.webp"
draft = false
+++

```python
from datetime import date

print(date.today().year, date.today().month)
# 2025 4
```

![issue-2025-04](splash.webp)

Welcome back and I'm glad to see you back reading the second issue of my "This month for Pythonistas" series which curates the news, articles, tutorials and more Python stuff worth noting in this April.

Before we continue, please note that this blog is synced across several platforms:

- [Github Pages](https://linzeyang.github.io/blog/post/this-month-for-pythonistas-2025-04/)
- [Netlify](https://blueberrypy.netlify.app/post/this-month-for-pythonistas-2025-04/)
- [Render](https://blueberrypy.onrender.com/post/this-month-for-pythonistas-2025-04/)

Ready? Let's get started!

---

## Events & Social

### DjangoCon Europe 2025

Dublin, Ireland is the host city of this year's DjangoCon Europe, which is held from April 23rd to 27th, 2025.

[djangocon europe website](https://2025.djangocon.eu/)

### EuroPython 2025

EuroPython has announced three more Keynote Speakers: Sebastián Ramírez (Creator os FastAPI, Typer, SQLModel, etc.), [Brett Cannon](https://www.linkedin.com/in/drbrettcannon/) (Python Core Developer), and [Petr Baudiš](https://www.linkedin.com/in/petr-baudis-906a213/) (co-founder and CTO of Rossum).

Besides, EuroPython will have a booth at PyCon US this year.

### Microsoft turns 50

Like it or not, Microsoft had remarkable influence over the past decades and is still making a big impact right at the moment. In [this page](https://unlocked.microsoft.com/50th/) it celebrates its 50th anniversary by looking back at some iconic moments from the history, sharing some stories, and giving out digital goodies.

### Discord server for free-threaded Python

There is a dedicated place to discuss free-threaded python on [Discord](https://discord.gg/rqgHCDqdRr) now.

### GvR BDFL (🤡 April Fools 🤡)

BREAKING! Guido van Rossum, the legendary creator of Python, has officially [reinstated himself as Benevolent Dictator for Life (BDFL)](https://www.youtube.com/watch?v=wgxBHuUOmjA).

![GvR BDFL](gvr_bdfl.jpg)

## New versions

### Python 3.13.3 & 3.12.10

It's another month for Python version updates.

Python 3.14 Alpha 7 is out, and the first beta release is expected soon.

Python 3.13 and 3.12 receive bugfix updates:
- [Python 3.13.3 Downloads and Release Notes](https://www.python.org/downloads/release/python-3133/)
- [Python 3.12.10 Downloads and Release Notes](https://www.python.org/downloads/release/python-31210/)

The following versions receive only security-related fixes and no binary distributions are provided: 3.11.12, 3.10.17 and 3.9.22.

### Visual Studio Code 1.99.0

VS Code joins Claude Desktop and other "AI IDEs", having [Agent Mode](https://code.visualstudio.com/docs/copilot/chat/chat-agent-mode) and [MCP servers support (Preview)](https://code.visualstudio.com/docs/copilot/chat/mcp-servers).

A new open-source and local MCP server is introduced, allowing integration with any LLM tool supporting MCP. Read the details in [Vibe coding with GitHub Copilot: Agent mode and MCP support rolling out to all VS Code users](https://github.blog/news-insights/product-news/github-copilot-agent-mode-activated/).

Update: Agent Mode is now officially turned on for everyone.

### Django 5.2 LTS

This LTS version introduces new features (Automatic model imports in the shell, Composite primary keys, etc.) and deprecates some functionalities, and it will receive security updates for the next three years at least. Check its [release notes](https://docs.djangoproject.com/en/5.2/releases/5.2/).

### PyTorch 2.7

[This release](https://pytorch.org/blog/pytorch-2-7/) introduces support for NVIDIA’s new Blackwell GPU architecture and ships pre-built wheels for CUDA 12.8. `TorchAudio` is updated to `2.7.0` and `TorchVision` is `0.22.0`.

### Ubuntu 25.04, Fedora 42, MX 23.6 and Manjaro 25.0

It seems like a big month for Linux distros since several popular distro have major/minor updates:
- [Ubuntu 25.04 "Plucky Puffin"](https://lists.ubuntu.com/archives/ubuntu-announce/2025-April/000311.html) introduces Linux 6.14 kernel, GNOME 48, and offers 9 months of support.
- [Fedora 42](https://fedoramagazine.org/announcing-fedora-linux-42/) promotes KDE Plasma variation to "Full Edition".
- [MX Linux](https://mxlinux.org/blog/mx-23-6-now-available/) is a regular refresh containing bugfixes, kernel updates, and application updates.
- [Manjaro 25.0 "Zetar"](https://forum.manjaro.org/t/manjaro-25-0-zetar-released/177008) brings various updates to different desktop environment editions.

## Tutorials

- Deeplearning.ai's [Vibe Coding 101 with Replit](https://www.deeplearning.ai/short-courses/vibe-coding-101-with-replit/) from replit

Take your own discretion on "Vibe Coding" (there's an article about it below), but here's a hands-on tutorial on deeplearning.ai.

> You’ll use Replit’s cloud environment— with an integrated code editor, package manager, and deployment tools—to build and deploy two web applications with the help of an AI coding agent. Along the way, you’ll learn strategies for working effectively with agents and improve your development skills in the process.

- Deeplearning.ai's [Getting Structured LLM Output](https://www.deeplearning.ai/short-courses/getting-structured-llm-output/) from DotTxt

> You’ll gain a fundamental understanding of structured outputs and learn efficient ways to generate outputs in your defined schema or format.

- Deeplearning.ai's [Building AI Browser Agents](https://www.deeplearning.ai/short-courses/building-ai-browser-agents/) from AGI Inc.

> Learn the fundamentals of autonomous web agents, what they are, how they work, their limitations, and the decision-making strategies taken to optimize their performance.

- Deeplearning.ai's [Building Code Agents with Hugging Face smolagents](https://www.deeplearning.ai/short-courses/building-code-agents-with-hugging-face-smolagents/) from HuggingFace

> Understand the architecture and benefits of code agents that write code to perform tasks, compare them to traditional tool-calling agents, and learn when to use each approach.

- RealPython's [Introducing DuckDB](https://realpython.com/python-duckdb/)

> The tutorial will equip you with the practical knowledge necessary to get started with DuckDB, including its Online Analytical Processing (OLAP) features, which enable fast access to data through query optimization and buffering.

- freeCodeCamp.org's [Code DeepSeek V3 From Scratch in Python](https://www.youtube.com/watch?v=5avSMc79V-w)

This is a nearly-4-hours Youtube video tutorial brought by freeCodeCamp.

- HuggingFace's [Agents Course](https://huggingface.co/learn/agents-course)

A series of tutorials introducing various aspects of AI Agents.

## Articles

- [Python's new t-strings](https://davepeck.org/2025/04/11/pythons-new-t-strings/)

[PEP 750 – Template Strings](https://peps.python.org/pep-0750/) is **accepted**. This PEP introduces *template strings* which are a generalization of *f-strings*. Putting a `t` before a string *template* would keep it from being evaluated as a normal string but make it an instance of a new type `Template`.

In his blog, Dave introduces the motivation behind this PEP and shows how to play with it.

- [PEP 751 – A file format to record Python dependencies for installation reproducibility](https://peps.python.org/pep-0751/)

PEP 751 is **accepted**. This PEP proposes a standard for the format of a file recording the requirements/dependencies of a Python project (ie. a lock file but standardized, agreed across the whole community).

Update:

`pip` 25.1+ adds experimental `pip lock` command:

```bash
pip lock -r .\requirements.txt --output pylock.toml
```

`uv` 0.6.15+ adds support through `uv export` command:

```bash
uv export --format pylock.toml --output-file pylock.toml
```

`pdm` 2.24+ also supports exporting to `pylock.toml`:

```bash
pdm export --format pylock --output pylock.toml
```

- [Share Python Scripts Like a Pro: uv and PEP 723 for Easy Deployment](https://thisdavej.com/share-python-scripts-like-a-pro-uv-and-pep-723-for-easy-deployment/)

> Sharing single-file Python scripts with external dependencies is now easy thanks to `uv` and PEP 723, which enable embedding dependency metadata directly within scripts.

- [Case Study: Developing and Testing Python Packages with uv](https://pybit.es/articles/developing-and-testing-python-packages-with-uv/)

This article highlights the simplicity of initializing a project with `uv`, which sets up essential files like `pyproject.toml`, `README.md`, and folder structures. This allows developers to manage dependencies effortlessly and set up virtual environments. It emphasizes the convenience of editable installations, enabling instant updates to package code without needing reinstallation.

- [The Llama 4 herd: The beginning of a new era of natively multimodal AI innovation](https://ai.meta.com/blog/llama-4-multimodal-intelligence/)

Meta has introduced Llama 4, its latest suite of multimodal AI models including "Llama 4 Scout" and "Llama 4 Maverick", offering significant advancements in personalized AI experiences. Both models utilize a mixture-of-experts (MoE) architecture, allowing efficient use of parameters: Maverick has 17 billion active parameters with 128 experts, while Scout offers a remarkable context length of 10 million tokens. "Llama 4 Behemoth", a larger model with 288 billion parameters, serves as a teacher for the others, enhancing their capabilities.

- [Agent Development Kit: Making it easy to build multi-agent applications](https://developers.googleblog.com/en/agent-development-kit-easy-to-build-multi-agent-applications/)

![google-vertex-ai-multi-agent](https://storage.googleapis.com/gweb-cloudblog-publish/images/Multi-agent_systems_with_Vertex_.max-2500x2500.jpg)

Google brings its own agent-building solution by announcing open-source framework **Agent Development Kit (ADK)** at [Google Cloud NEXT 2025](https://cloud.withgoogle.com/next/25), additionally it introduces [Agent2Agent (A2A) protocol](https://developers.googleblog.com/en/a2a-a-new-era-of-agent-interoperability/), [Agent Engine](https://cloud.google.com/vertex-ai/generative-ai/docs/agent-engine/overview) as well as [Agent Garden](https://console.cloud.google.com/vertex-ai/agents/agent-garden).

- [Introducing GPT-4.1 in the API](https://openai.com/index/gpt-4-1/)

GPT‑4.1, GPT‑4.1 mini, and GPT‑4.1 nano are available through OpenAI's API service. These new models appear to focus mainly on coding and instruction following.

Update: They are also available through Github Models.

- [Introducing OpenAI o3 and o4-mini](https://openai.com/index/introducing-o3-and-o4-mini/)

OpenAI then release o3 and o4-mini of the o-series models, claiming they are their "smartest" models to date.

- [The role of developer skills in agentic coding](https://martinfowler.com/articles/exploring-gen-ai.html#memo-13)

This article discusses the role of developer skills in agentic coding with AI assistants. The author categorizes AI missteps into three impact radius: time to commit, team flow, and long-term maintainability. The article emphasizes the need for developer oversight, caution against "good enough" solutions, and the importance of code quality practices and team communication.

- [MCP (Model Context Protocol): Simply explained in 5 minutes](https://read.highgrowthengineer.com/p/mcps-simply-explained)

![mcp-diagram](https://substackcdn.com/image/fetch/f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F6de5b04a-5e6c-47cf-a81e-e332dd3570df_2906x990.png)

Model Context Protocol is a way for LLMs to integrate with external tools. It is useful as it makes LLMs act more like developers. Behind the scenes, providers create MCP-compliant wrappers. Resources for MCP are also provided.

- [MCP - It's Hot, But Will It Win?](https://hardcoresoftware.learningbyshipping.com/p/230-mcp-its-hot-but-will-it-win)

In the author's point of view, while MCP is popular, its success is uncertain. Middleware like MCP often fails to live up to expectations. It may face issues such as monetization problems if widely adopted or exclusion by a key platform. Vendors may lose interest due to market realities.

- [The "S" in MCP stands for Security](https://elenacross7.medium.com/%EF%B8%8F-the-s-in-mcp-stands-for-security-91407b33ed6b)

Despite its benefits, such as standardized APIs and persistent sessions, MCP has significant security risks. These risks include potential side-channels into shells, secrets, or infrastructure when agents are connected to arbitrary servers without proper security measures. The author emphasizes the need for better security in MCP to prevent these vulnerabilities.

- [MCP vs. A2A: Friends or Foes?](https://www.newsletter.swirlai.com/p/mcp-vs-a2a-friends-or-foes)

MCP standardizes how applications integrate with large language models (LLMs), while A2A facilitates communication between agents across different systems. Although MCP currently excels in establishing context for LLMs, it lacks essential features like security and task management, which A2A addresses. As both protocols evolve, their roles may intertwine, but A2A appears poised for dominance in inter-agent communication, potentially overshadowing MCP's relevance in the future.

- [Git turns 20: A Q&A with Linus Torvalds](https://github.blog/open-source/git/git-turns-20-a-qa-with-linus-torvalds/)

![git-turns-twenty](https://github.blog/wp-content/uploads/2025/04/GitTurns20_BlogHeader_001-2.png?w=1600)

To celebrate two decades of Git, the author sat down with Linus himself to revisit those early days, explore the key design decisions behind Git’s lasting success, and discuss how it forever changed software development. The full video interview is also included in the blog.

- [Karpathy’s ‘Vibe Coding’ Movement Considered Harmful](https://nmn.gl/blog/dangers-vibe-coding)

The author argues that Karpathy's "vibe coding" is harmful. It leads to hidden costs, exponential technical debt, and security risks. A better approach is to use AI with a clear vision, break down AI-generated code, provide context, test thoroughly, and review code to maintain understanding.

- [Training and Finetuning Reranker Models with Sentence Transformers v4](https://huggingface.co/blog/train-reranker)

In this blogpost, the author shows how to use sentence-transformers to finetune a reranker model that beats all existing options on exactly your data. This method can also train extremely strong new reranker models from scratch.

## Podcasts

### 🥝 core.py

- [Episode 21: A Garbage Episode](https://open.spotify.com/episode/6UTlYsa61miMc9vwCaAyWm)

### 🐍 RealPython Podcast

- [Episode 245: GUIs & TUIs: Choosing a User Interface for Your Python Project](https://realpython.com/podcasts/rpp/245/)
- [Episode 246: Learning Intermediate Python With a Deep Dive Course](https://realpython.com/podcasts/rpp/246/)
- [Episode 247: Exploring DuckDB & Comparing Python Expressions vs Statements](https://realpython.com/podcasts/rpp/247/)

### 🥧 Python Bytes Podcast

- [#426 Committing to Formatted Markdown](https://pythonbytes.fm/episodes/show/426/committing-to-formatted-markdown)
- [#427 Rise of the Python Lord](https://pythonbytes.fm/episodes/show/427/rise-of-the-python-lord)
- [#428 How old is your Python?](https://pythonbytes.fm/episodes/show/428/how-old-is-your-python)
- [#429 Nitpicking Python](https://pythonbytes.fm/episodes/show/429/nitpicking-python)
- [#430 Or you go to jail](https://pythonbytes.fm/episodes/show/430/or-you-go-to-jail)

### 🦜 Talk Python to me

- [#499: BeeWare and the State of Python on Mobile](https://talkpython.fm/episodes/show/499/beeware-and-the-state-of-python-on-mobile)
- [#500: Django Simple Deploy and other DevOps Things](https://talkpython.fm/episodes/show/500/django-simple-deploy-and-other-devops-things)
- [#501: Marimo - Reactive Notebooks for Python](https://talkpython.fm/episodes/show/501/marimo-reactive-notebooks-for-python)
- [#502: Django Ledger: Accounting with Python](https://talkpython.fm/episodes/show/502/django-ledger-accounting-with-python)
- [#503: The PyArrow Revolution](https://talkpython.fm/episodes/show/503/the-pyarrow-revolution)

### 🍕 Pybites Podcast

- [#185: Expanding the world of Pybites with cohort coaching, book platforms and more!](https://www.pybitespodcast.com/1501156/episodes/16903500-185-expanding-the-world-of-pybites-with-cohort-coaching-book-platforms-and-more)
- [#186: Rethinking the art of coding](https://www.pybitespodcast.com/1501156/episodes/16944372-186-rethinking-the-art-of-coding)
- [#187: Beyond the resume - how to stand out in the competitive world of tech](https://www.pybitespodcast.com/1501156/episodes/16974259-187-beyond-the-resume-how-to-stand-out-in-the-competitive-world-of-tech)
- [#188: Career crossroads - navigating the path to job fulfillment](https://www.pybitespodcast.com/1501156/episodes/17013337-188-career-crossroads-navigating-the-path-to-job-fulfillment)

## Repositories

### `google/adk-python` (Apache-2.0)

[source](https://github.com/google/adk-python)

### `awslabs/mcp` (Apache-2.0)

[source](https://github.com/awslabs/mcp)

### `github-mcp-server` (MIT)

![github-mcp-server](https://github.com/user-attachments/assets/a2926942-1c3d-4f95-bb73-861d8003aecb)

[source](https://github.com/github/github-mcp-server)

### `InternVL3-78B`

[source](https://huggingface.co/OpenGVLab/InternVL3-78B)

### `moonshotai/Kimi-VL-A3B-Thinking`

[source](https://huggingface.co/moonshotai/Kimi-VL-A3B-Thinking)

### `THUDM/GLM-Z1-32B-0414`

[source](https://huggingface.co/THUDM/GLM-Z1-32B-0414)

### `Qwen 3`

[source](https://huggingface.co/Qwen/Qwen3-235B-A22B)

## Have time for some fun?

### Nintendo Switch 2 has a launch date

![nintendo-switch-2](https://assets-prd.ignimgs.com/2025/01/16/screenshot-161-1737034377908.png)

Nintendo reveals in their "Direct" livestream event that Switch 2 is available on June 5th, 2025 worldwide with starting price ~$449.99 outside Japan (multi-language version) and a much lower price inside Japan (Japanese-only version). Read more about it on their [official website](https://www.nintendo.com/us/gaming-systems/switch-2/).

### Clair Obscur: Expedition 33 sets sail on April 24th

In this dark fantasy RPG inspired by JRPG and Soul-like games and made by a small French team "Sandfall Interactive", players will explore the mysterious city of Lumière and engage in immersive turn-based battles with unique mechanics. After playing it for around 30 hours I must say I really enjoyed the visual style and the rewarding action part in the battles. Check their [official website](https://www.expedition33.com/) for more info.

---

Alright, that concludes the second issue of "This Month of Pythonistas". Thank you again for reading my post. I hope you enjoy it or find something useful, and see you in May!
