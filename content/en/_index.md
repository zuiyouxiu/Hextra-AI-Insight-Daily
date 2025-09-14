---
linkTitle: AI Daily
title: AI Daily-AI资讯日报
breadcrumbs: false
next: /en/2025-09/2025-09-14
description: Your daily source for curated AI news, practical tools, and actionable
  tutorials to master Artificial Intelligence;
cascade:
  type: docs
---
## AI News Daily 2025/9/15

> AI News | Daily Briefing | Web Data Aggregation | Cutting-Edge Science Exploration | Industry Free Voice | Open Source Innovation Power | AI and Human Future | [Visit Web Version ↗️](https://ai.hubtoday.app/) | [Join Group Chat 🤙](https://raw.githubusercontent.com/justlovemaki/CloudFlare-AI-Insight-Daily/main/docs/images/wechat.png)

### **Today's Summary**

```
Xiaohongshu has rolled out its open-source conversational model, FireRedTTS-2, aiming to boost the realism of AI-generated voices.
A new UQ benchmark is putting large language models to the test with real-world scientific problems, revealing the current limitations of AI.
OpenAI research suggests that completely eradicating AI hallucinations might be impossible, potentially stifling models' creativity and fluency.
Industry trends are uncovering the hidden human costs behind AI and the risks of replacing senior developers with AI.
Simultaneously, the role of programmers is undergoing a profound transformation, potentially shifting to configuring and quality-checking AI systems in the future.
```

### Product & Feature Updates
1. The `Xiaohongshu Smart Creation team` has dropped a bombshell, releasing their conversational generation model, **FireRedTTS-2**. The goal? To make AI podcasts sound less like robots reading a script. ✨ This model tackles industry pain points like mispronunciations, awkward rhythm, and unstable speaker switching by upgrading its discrete speech encoder and TTS model. According to [this technical report (AI News)](https://arxiv.org/pdf/2509.02020), its performance is already top-tier. Even more impressively, it can clone a voice from a single audio clip and has open-sourced its [relevant code (AI News)](https://github.com/FireRedTeam/FireRedTTS2)! This is a huge gift for content creators, and [this news report (AI News)](https://www.jiqizhixin.com/articles/2025-09-14-2) provides all the juicy details. 🚀<br/>![AI News: FireRedTTS-2 Model Architecture Diagram](https://source.hubtoday.app/images/2025/09/news_01k54dcc0qfb2bhgfvf7nwrp66.avif)<br/>![AI News: FireRedTTS-2 vs. Other Models Comparison](https://source.hubtoday.app/images/2025/09/news_01k54dc985e4fvk0yhfjzwzw8s.avif)<br/>

### Cutting-Edge Research
1. Current large model benchmarks are either too "nerdy" or too "naively simple." So, `researchers from Stanford and the University of Washington` have unveiled the ultimate testing ground: **UQ (Unsolved Questions)**. This dataset packs 500 truly unresolved problems from science, math, and other fields. According to [this paper (AI News)](https://arxiv.org/pdf/2508.17580v1), even top-tier models like **o3 Pro** only ace 15% of the questions – a true "hell mode" challenge for AI! What's even cooler is they've set up an [UQ-Platform open platform (AI News)](https://uq.stanford.edu/), which continuously updates and validates problems through community input, transforming model evaluation from a one-time exam into a dynamically evolving process. 🤯<br/>![AI News: UQ Dataset Filtering Process](https://source.hubtoday.app/images/2025/09/news_01k54daz60fmhs1fnj738mr1n8.avif)<br/>
2. Can we save `AI from its straight-faced fibs`? OpenAI's latest research spills a harsh truth: completely eliminating "**hallucinations**" might be an impossible mission. [The Conversation's in-depth analysis (AI News)](https://theconversation.com/why-openais-solution-to-ai-hallucinations-would-kill-chatgpt-tomorrow-265107) points out that fixing hallucinations could actually kill ChatGPT's creativity and fluency, turning it into a dull, uninteresting bot. Looks like we might just have to accept AI as a somewhat "Pinocchio-esque" companion. The key won't be eradicating the lies, but rather learning to live with them. 🤥

### Industry Outlook & Social Impact
1. What kind of "sweatshop" lies behind `Google AI's` shiny facade? An [in-depth report from The Guardian (AI News)](https://readhacker.news/s/6BzeH) pulls back the curtain, revealing thousands of "overworked, underpaid" contract workers labeling data for AI models under harsh deadlines and opaque conditions. The article sharply notes that it's the relentless grind of these human annotators that makes chatbots appear "smart." This makes you wonder: in an era of rapid AI advancement, are we overlooking the real human costs behind it all? 🤔
2. An [anonymous Reddit post (AI News)](https://www.reddit.com/r/artificial/comments/1ngakf8/companies_are_laying_off_senior_devs_and/) paints a disturbing picture: `large companies` are ditching experienced senior developers, instead relying on AI systems and junior staff. This whole maneuver has directly led to buggy systems and customer service meltdowns, with AI-driven IT ticketing systems only adding fuel to the fire. This isn't just an isolated case; it feels more like a "corporate virus" spreading, trading short-term cost cuts for long-term systemic risks. 📉
3. Is `the future of programmers` not about coding, but about being "AI wranglers"? A trending [Reddit post (AI News)](https://www.reddit.com/r/artificial/comments/1ngomca/hot_take_the_future_of_coding_no_more_manual/) throws out a bold idea: developers' roles will shift from code writers to configurators and QA testers for AI agents. The analogy is spot-on: much like factory workers adjust malfunctioning machines instead of fixing individual defects, future developers will optimize AI systems to churn out high-quality code. This hints at a profound identity shift coming to software engineering. Are you ready? 👨‍🔧
4. Whose data is it anyway? `Spotify` recently got super peeved because 10,000 users sold their listening data to a third party to build AI tools. This incident sparked huge debate on [Reddit (AI News)](https://www.reddit.com/r/artificial/comments/1ng38nn/spotify_peeved_after_10000_users_sold_data_to/), perfectly exposing the gray area between user data ownership and platform terms of service. This isn't just a data privacy squabble; it's a profound challenge to the value of personal assets in the digital age. 🤔<br/>![AI News: Spotify User Data Sale Incident](https://source.hubtoday.app/images/2025/09/news_01k54db19rfstber9qh1fjgwca.avif)<br/>

### Open Source TOP Projects
1. To feed the hungry AI large models, a web crawler specifically designed for LLMs, `crawl4ai`, has burst onto the scene, solving the paramount challenge of data acquisition. This open-source project, which has already snagged a whopping ⭐52.8k stars on [GitHub (AI News)](https://github.com/unclecode/crawl4ai), scrapes web content and converts it into an LLM-friendly format, making it a "data granary" for RAG applications and model training. For any developer looking to arm their models with fresh, high-quality web data, this is an absolute must-have tool! 🔥
2. `AI researchers` now have their own "digital doppelgänger": **DeepResearchAgent**, a multi-agent system capable of simulating research teams for in-depth exploration. This innovative framework, which has racked up ⭐1.7k stars on [GitHub (AI News)](https://github.com/SkyworkAI/DeepResearchAgent), uses a "top-level planning agent" to orchestrate multiple "bottom-level expert agents," enabling automatic task decomposition and efficient execution. It's more than just a tool; it's a brand-new, automated paradigm for tackling complex problems. 🚀
3. `Mac users` can finally get their groove on with LLMs locally, all thanks to Apple's own team and their **mlx-lm** project. This toolkit, built on the **MLX** framework, makes running, fine-tuning, and training large language models on Apple Silicon incredibly efficient, having already scored ⭐1.9k stars on [GitHub (AI News)](https://github.com/ml-explore/mlx-lm). With this, your MacBook can transform into a powerful, portable AI workstation! 🤩
4. `Docker` is paving a wider cloud-native highway for developers, and the new project **mcp-gateway** is the latest landmark. As a CLI plugin and gateway designed for MCP (Multi-Component Portable), it signals that managing complex distributed applications is about to get way simpler. This project in [Docker's official repository (AI News)](https://github.com/docker/mcp-gateway) is already pulling in nearly ⭐400 followers. Keep a close eye on it—this could be a game-changer for streamlining future multi-component app deployments! ✨

### Social Media Shares
1. In the fierce battle of AI app stores, the tide seems to have turned overnight. A chart gone viral on [social media (AI News)](https://x.com/op7418/status/1967102525225762974) shows `Gemini App's` user growth curve suddenly skyrocketing, overtaking the veteran champion ChatGPT in one fell swoop. This chart, paired with the classic line "Slowly then suddenly," perfectly encapsulates the brutal drama of the tech world. Looks like Google's mobile AI strategy is finally flexing its muscles! 🔥<br/>![AI News: Gemini App User Growth Chart](https://source.hubtoday.app/images/2025/09/news_01k54db4q0fay8d3yanjdqfj64.avif)<br/>
2. `AI` is no longer just about "tweaking parameters"; it's evolved into a complex "**full-stack engineering**" challenge, demanding the complete integration of data, training, deployment, and the business loop. A seasoned pro, in [this insightful tweet (AI News)](https://x.com/shao__meng/status/1967212895395365252), meticulously compiled 9 must-read bibles in the AI engineering domain—a complete upgrade path from novice to expert. This reading list is your battle map to transform from a model user into an AI architect. Go ahead and save it for your studies! 🛠️<br/>![AI News: Essential AI Engineering Books Cover 1](https://source.hubtoday.app/images/2025/09/news_01k54db7ccfvy96jw2fbv2ffvg.avif)<br/>
3. The highly anticipated `open-source TTS models` of this year — do their actual results live up to their "seller show" promotions? One developer sharply clapped back on a [social platform (AI News)](https://x.com/oran_ge/status/1966988384901255322), claiming that some open-source versions of models are miles away from their promo videos, with results like chalk and cheese compared to the "buyer show" and "seller show." This "photoshopping" models just to grab eyeballs, much like those deceptive pics on Xiaohongshu, is eroding community trust. He's calling for less marketing fluff and more genuine open-sourcing. 😒
4. If `you could travel back to ancient Rome` for a day, what would you learn to advance modern tech, and what would you do to get rich overnight? Wharton Professor Ethan Mollick used this wild thought experiment to conduct a fun "stress test" on three top-tier AIs, sharing the results on [his social media (AI News)](https://x.x.com/emollick/status/1967009330789589077). The AIs' answers were both creative and historically insightful, earning a "pretty good" rating from the professor, fully showcasing their amazing potential in tackling complex, open-ended questions. 💡<br/>![AI News: AI Answers Time Travel Question 1](https://source.hubtoday.app/images/2025/09/news_01k54dbk0bem5se8pq3vn97y5x.avif)<br/>![AI News: AI Answers Time Travel Question 2](https://source.hubtoday.app/images/2025/09/news_01k54dbpn4f03sg8b0dcn05kqp.avif)<br/>

---

## **An AI Coding Invitation**

### 3 Projects in Half a Year, 90% Code by AI, Zero Cost — I'm Building a Community and Live-Streaming My Next Product Development

Hey everyone,

Over the past six months, `I've been a lone wolf`, diving deep and completing 3 major open-source projects, one of which, [AIClient2API ↗️](https://github.com/justlovemaki/AIClient-2-API), already boasts over 1000 stars. The craziest part? Looking back, `over 90% of the code was generated by AI`.

`I didn't pay a single dime in API fees` for any of this, relying entirely on free large models like Gemini and Qwen. Nor did I shell out for servers, with platforms like Cloudflare and Vercel shouldering all the load for me. This whole experience really hammered home one thing: **AI is amplifying the creativity of everyday folks in unprecedented ways.**

While the `solo journey` was super fulfilling, it definitely got a bit lonely. All those moments of hitting roadblocks, those flashes of inspiration in the dead of night—I always wished for fellow travelers to share and bounce ideas off.

So, `I had an idea`: **to create a knowledge planet (community) and gather all the passionate, creative folks who love to tinker.**

This isn't your `traditional course`; it's a genuine co-creation community. The price point? Not steep at all: **50 RMB**. Think of it as our "Crazy Thursday" — we'll grab some fried chicken together, make friends, and forge a pact for mutual growth.

**Join Us, What Will You Get?**

`I'm gearing up to develop a **personal prompt management tool** from scratch`. Once our community hits 7 members, we'll officially kick things off. In the community, I'll be:

*   **Daily Live-Stream Updates**: Documenting my development progress, thought process, and tech stack choices from start to finish.
*   **Real-Talk on Pitfalls**: Unreservedly sharing the issues I hit and my thought process for bug fixing, helping you avoid common detours.
*   **Transparent Thought Process**: Whether it's product design or technical architecture, I'll share all the behind-the-scenes thinking with you.

Here, `you can witness a product's birth, ask questions anytime, jump into discussions, and even influence its direction`. Together, we'll watch an idea evolve from zero to one, eventually becoming a tangible reality in your hands.

If `you're also hyped about AI development`, and curious to see how one person can "arm" themselves with free tools, then welcome aboard!

![Knowledge Planet QR Code](https://source.hubtoday.app/logo/zsxq.jpg)

---

## **AI News Daily Voice Version**

| 🎙️ **Laisheng Xiaojiuguan (Little Tavern of the Afterlife)** | 📹 **Self-Media Account** |
| --- | --- |
| [Laisheng Xiaojiuguan (Little Tavern of the Afterlife)](https://www.xiaoyuzhoufm.com/podcast/683c62b7c1ca9cf575a5030e) | [Self-Media Account](https://www.douyin.com/user/MS4wLjABAAAAwpwqPQlu38sO38VyWgw9ZjDEnN4bMR5j8x111UxpseHR9DpB6-CveI5KRXOWuFwG)|
| ![Laisheng Xiaojiuguan](https://source.hubtoday.app/logo/f959f7984e9163fc50d3941d79a7f262.md.png) | ![Intelligence Station](https://source.hubtoday.app/logo/7fc30805eeb831e1e2baa3a240683ca3.md.png) |