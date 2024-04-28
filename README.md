# RAG with agents - multiple sources(wiki, PDFs, texts , ARXiv)

# Tools are interface that an agent, chain or LLM can use to interact with the world.

suppose we have dependeny on folowing data sources ((wiki, PDFs, texts, ARXiv), we want tou integrate all these sources as wappers so we could implement this QA solution.

we'll use

1. Tools -> tooklits
2. Agents

we can use each source as different tool. and we can wrap all of these sources as toolkit. and, then, with helpp of agesmts we'll be able to every sort of QA search.

# Agents are to use LM to choose a sequence of actions to take

# In chains sequence of actions is hardcoded

# so our agent will first look in wiki, if unsuccessful, then look in arxiv
