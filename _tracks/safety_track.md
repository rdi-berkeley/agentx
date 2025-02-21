---
title: Safety Track
description: Address critical safety concerns in AI agent deployment, including preventing misuse, ensuring privacy, improving interpretability, and assessing broader societal impacts. Develop methods for better control, auditing, and accountability of AI agents in various applications and multi-agent systems.
date: 2020-01-04 14:40:45
---

<div style="text-align: center;">
  <h1 style="font-weight: bold; font-size: 3em; color: #CB9445;">Program Task Description</h1>
</div>

<h2>Category 1: Preventing Accidental Misuse</h2>
<ul>
   <li>
      How will hallucinations and bias in LLM agents differ from typical LLMs? What novel mitigations do we need to develop? 
      <ul>
         <li>
            Reduce the amount of wasteful or harmful API calls in tool-based LLM agents through either software-based or ML-based solutions
        </li>
        <li>
          <a href="https://arxiv.org/abs/2305.15334">[2305.15334] Gorilla: Large Language Model Connected with Massive APIs</a>
        </li>
      </ul>
   </li>
    <li>
      What are some unintended consequences of deploying LLM agents? 
      <ul>
         <li>
            Demonstrate a novel failure mode of LLM agents 
        </li>
        <li>
          <a href="https://arxiv.org/abs/2402.06627">[2402.06627] Feedback Loops With Language Models Drive In-Context Reward Hacking</a>
        </li>
        <li>
          <a href="https://arxiv.org/abs/2402.06664">[2402.06664] LLM Agents can Autonomously Hack Websites</a>
        </li>
      </ul>
   </li>
</ul>

<h2>Category 2: Preventing Malicious Use</h2>
<ul>
   <li>
      How do we attack and defend LLM agents? Will this paradigm differ from standard jailbreaking of LLMs? 
      <ul>
         <li>
            Create novel prompt injection attacks or demonstrate a novel defense for LLM agents  
        </li>
        <li>
          <a href="https://arxiv.org/abs/2311.01011">[2311.01011] Tensor Trust: Interpretable Prompt Injection Attacks from an Online Game</a>
        </li>
        <li>
          <a href="https://arxiv.org/abs/2402.06363">[2402.06363] StruQ: Defending Against Prompt Injection with Structured Queries</a>
        </li>
      </ul>
   </li>
  <li>
      What privacy challenges will LLM agents face? How can we mitigate these? 
      <ul>
         <li>
            Design a novel differentially private training method to train agents on user trajectories while hiding PII  
        </li>
        <li>
          <a href="https://arxiv.org/abs/2401.05459">[2401.05459] Personal LLM Agents: Insights and Survey about the Capability, Efficiency and Security</a>
        </li>
        <li>
          <a href="https://arxiv.org/abs/2407.19354">[2407.19354] The Emerged Security and Privacy of LLM Agent: A Survey with Case Studies</a>
        </li>
      </ul>
   </li>
  <li>
      How do we prevent LLM agents from being directed to create bioweapons or cyberweapons? 
      <ul>
         <li>
            Analyze the difficult of creating a novel cyberweapon with an LLM  
        </li>
        <li>
          <a href="https://openai.com/index/building-an-early-warning-system-for-llm-aided-biological-threat-creation/">Building an early warning system for LLM-aided biological threat creation | OpenAI</a>
        </li>
        <li>
          <a href="https://arxiv.org/abs/2403.03218">[2403.03218] The WMDP Benchmark: Measuring and Reducing Malicious Use With Unlearning</a>
        </li>
      </ul>
   </li>
</ul>

<h2>Category 3: Steering, Controlling, and Interpreting Agents</h2>
<ul>
   <li>
      How do we better specify user objectives and safety constraints in LLM agents to eliminate unintended consequences? 
      <ul>
         <li>
            Develop techniques that encourage LLMs to follow hard constraints  
        </li>
        <li>
            <a href="https://arxiv.org/abs/2311.04235">[2311.04235] Can LLMs Follow Simple Rules?</a>  
        </li>
        <li>
            <a href="https://arxiv.org/abs/2402.10962">[2402.10962] Measuring and Controlling Instruction (In)Stability in Language Model Dialogs</a>  
        </li>
        <li>
            <a href="https://arxiv.org/abs/2404.13208">[2404.13208] The Instruction Hierarchy: Training LLMs to Prioritize Privileged Instructions</a>  
        </li>
      </ul>
   </li>
  <li>
      How do we give users insight into agent behaviors and steer them more reliably? 
      <ul>
         <li>
            Create a visualization of how LLM objectives evolves as they solve tasks  
        </li>
        <li>
            <a href="https://arxiv.org/abs/2305.02469">[2305.02469] The System Model and the User Model: Exploring AI Dashboard Design</a>  
        </li>
        <li>
            <a href="https://arxiv.org/abs/2309.08600">[2309.08600] Sparse Autoencoders Find Highly Interpretable Features in Language Models</a>  
        </li>
        <li>
            <a href="https://arxiv.org/abs/2310.01405">[2310.01405] Representation Engineering: A Top-Down Approach to AI Transparency</a>  
        </li>
        <li>
            <a href="https://arxiv.org/abs/2403.10949">[2403.10949] SelfIE: Self-Interpretation of Large Language Model Embeddings</a>  
        </li>
      </ul>
   </li>
</ul>

<h2>Category 4: Auditing and Accountability</h2>
<ul>
   <li>
      How do we better evaluate and audit LLM agents?
      <ul>
         <li>
            Develop methods to automatically red-team agents  
        </li>
        <li>
            <a href="[https://example.com](https://arxiv.org/abs/2309.15817)">[2309.15817] Identifying the Risks of LM Agents with an LM-Emulated Sandbox</a>  
        </li>
      </ul>
   </li>
  <li>
      How do we monitor and hold LLM agents accountable for their actions?
      <ul>
         <li>
            Create techniques that identify dangerous actions in AI agent trajectories  
        </li>
        <li>
            <a href="https://arxiv.org/abs/2401.13138">[2401.13138] Visibility into AI Agents</a>  
        </li>
      </ul>
   </li>
</ul>

<h2>Category 5: Multi-Agent Safety and Security</h2>
<ul>
   <li>
      What novel failure modes occur in multi-agent systems? 
      <ul>
         <li>
            Analyze collusion between agents or correlated failures among agents
        </li>
        <li>
            <a href="https://arxiv.org/abs/2308.01404">[2308.01404] Hoodwinked: Deception and Cooperation in a Text-Based Game for Language Models</a>  
        </li>
        <li>
            <a href="https://arxiv.org/abs/2402.07510">[2402.07510] Secret Collusion Among Generative AI Agents</a>  
        </li>
        <li>
            <a href="https://arxiv.org/abs/2404.00806">[2404.00806] Algorithmic Collusion by Large Language Models</a>  
        </li>
      </ul>
   </li>
</ul>

<h2>Category 6: Environmental and Societal Impact of Agents</h2>
<ul>
   <li>
      What will be the environmental cost of agents? 
      <ul>
         <li>
            Design a project that estimates the carbon emissions cost of deploying an agent on a task
        </li>
        <li>
            <a href="https://arxiv.org/abs/2111.00364">[2111.00364] Sustainable AI: Environmental Implications, Challenges and Opportunities</a>  
        </li>
      </ul>
   </li>
  <li>
      Are agents fair? How might their deployment impact societal values or influence economic incentives? How should we govern them? 
      <ul>
         <li>
            Study how LLM agents may affect a particular sector of society, e.g., how will LLMs lead to content homogenization
        </li>
        <li>
            <a href="https://www.vox.com/future-perfect/23674696/chatgpt-ai-creativity-originality-homogenization">What happens when ChatGPT starts to feed on its own writing?</a>  
        </li>
        <li>
            <a href="https://arxiv.org/abs/2407.14981">[2407.14981] Open Problems in Technical AI Governance</a>  
        </li>
      </ul>
   </li>
</ul>
