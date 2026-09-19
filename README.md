# Hey, I'm Jacopo.

I'm a quantitative researcher working across two threads: systematic equity alpha research, and the economics of AI agents in markets.

## Systematic equity alpha research

My work in alpha research has centered on alternative data, big data, and machine learning: finding signal in unstructured and non-obvious datasets and taking it end to end, from raw data through backtesting, risk, and portfolio construction. I came up in alpha research at BlackRock Systematic Active Equity and Point72, where the data is a commodity anyone can buy and the edge is entirely in the insight.

**alpha-decay-foundry** is the research infrastructure I build this on: a bitemporal, look-ahead-safe data store over SEC EDGAR and pricing data, machine-learning signal research, and defensible-backtest machinery in the tradition of Lopez de Prado (walk-forward with purging and embargo, deflated Sharpe and PBO for overfitting control, transaction costs, a risk model with neutralization, convex portfolio optimization). A broad characteristics library sits underneath as a baseline layer; the research that matters lives above it. I run a personal systematic equity book on top. Private for now.

## AI agents in markets

AI agents are moving from tools to participants in financial markets. Institutions are shifting from rule-based algorithmic trading toward LLM-based agents that synthesize signals, draft orders, and manage risk within defined limits, a pattern researchers describe as bounded-autonomy trading. My question: as decision authority in markets moves from humans to these agents, do the classical guarantees markets are designed around (strategy-proofness, efficiency, price discovery, credibility) still hold when the participants are LLMs, or does market design need to be rebuilt for agents as participants?

**agent-market-harness** is a Python harness that places scripted and LLM agents inside canonical market mechanisms (second-price, first-price, English auctions) and tests whether those guarantees survive under LLM participants, benchmarked against Bayes-Nash equilibrium. It is a multi-agent model of price formation: heterogeneous agents competing inside a market, instrumented so every decision is recorded as data. Working paper in progress; private for now, opening once results are ready.

Working paper (planned): *Prompts as incentive contracts: delegation to market agents.*

## Publications

Au Yeung, J., Dalmasso, J., Foschini, L., Dobson, R.J., Kraljevic, Z. *The Psychogenic Machine: Simulating AI Psychosis, Delusion Reinforcement and Harm Enablement in Large Language Models.* arXiv preprint, 2025. A different field (LLM safety, not markets), but the closest prior work to the empirical benchmark methodology this research uses. arXiv:2509.10970

## Background

Before this, most of my career was in decision science and applied AI/ML across finance, health, and technology.

- Quantitative Researcher, BlackRock Systematic Active Equity (alternative data, NLP, statistical arbitrage; co-led the Data Discovery group)
- VP Data Science, Point72 (alternative-data alpha across sectors; backtesting and portfolio-optimization infrastructure)
- Co-founder and COO (previously VP AI and Product Engineering), Nuraxi (privacy-preserving health AI)
- Co-founder and CEO, Lyta (financial due-diligence AI)
- Earlier data/ML roles at Knotel

## Get in touch

## Get in touch

[LinkedIn](https://www.linkedin.com/in/jacopodalmasso/) · [Email](mailto:jacopo.dalmasso@gmail.com)
