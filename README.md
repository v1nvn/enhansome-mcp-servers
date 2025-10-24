# Awesome MCP Servers [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) with stars

[![ไทย](https://img.shields.io/badge/Thai-Click-blue)](origin/README-th.md)
[![English](https://img.shields.io/badge/English-Click-yellow)](origin/README.md)
[![繁體中文](https://img.shields.io/badge/繁體中文-點擊查看-orange)](origin/README-zh_TW.md)
[![简体中文](https://img.shields.io/badge/简体中文-点击查看-orange)](origin/README-zh.md)
[![日本語](https://img.shields.io/badge/日本語-クリック-青)](origin/README-ja.md)
[![한국어](https://img.shields.io/badge/한국어-클릭-yellow)](origin/README-ko.md)
[![Português Brasileiro](https://img.shields.io/badge/Português_Brasileiro-Clique-green)](origin/README-pt_BR.md)
[![Discord](https://img.shields.io/discord/1312302100125843476?logo=discord\&label=discord)](https://glama.ai/mcp/discord)
[![Subreddit subscribers](https://img.shields.io/reddit/subreddit-subscribers/mcp?style=flat\&logo=reddit\&label=subreddit)](https://www.reddit.com/r/mcp/)

A curated list of awesome Model Context Protocol (MCP) servers.

* [What is MCP?](#what-is-mcp)
* [Clients](#clients)
* [Tutorials](#tutorials)
* [Community](#community)
* [Legend](#legend)
* [Server Implementations](#server-implementations)
* [Frameworks](#frameworks)
* [Tips & Tricks](#tips-and-tricks)

## What is MCP?

[MCP](https://modelcontextprotocol.io/) is an open protocol that enables AI models to securely interact with local and remote resources through standardized server implementations. This list focuses on production-ready and experimental MCP servers that extend AI capabilities through file access, database connections, API integrations, and other contextual services.

## Clients

Checkout [awesome-mcp-clients](https://github.com/punkpeye/awesome-mcp-clients/) ⭐ 5,891 | 🐛 47 | 📅 2025-09-01 and [glama.ai/mcp/clients](https://glama.ai/mcp/clients).

> \[!TIP]
> [Glama Chat](https://glama.ai/chat) is a multi-modal AI client with MCP support & [AI gateway](https://glama.ai/gateway).

## Tutorials

* [Model Context Protocol (MCP) Quickstart](https://glama.ai/blog/2024-11-25-model-context-protocol-quickstart)
* [Setup Claude Desktop App to Use a SQLite Database](https://youtu.be/wxCCzo9dGj0)

## Community

* [r/mcp Reddit](https://www.reddit.com/r/mcp)
* [Discord Server](https://glama.ai/mcp/discord)

## Legend

* 🎖️ – official implementation

* programming language
  * 🐍 – Python codebase
  * 📇 – TypeScript (or JavaScript) codebase
  * 🏎️ – Go codebase
  * 🦀 – Rust codebase
  * \#️⃣ - C# Codebase
  * ☕ - Java codebase
  * 🌊 – C/C++ codebase
  * 💎 - Ruby codebase

* scope
  * ☁️ - Cloud Service
  * 🏠 - Local Service
  * 📟 - Embedded Systems

* operating system
  * 🍎 – For macOS
  * 🪟 – For Windows
  * 🐧 - For Linux

> \[!NOTE]
> Confused about Local 🏠 vs Cloud ☁️?
>
> * Use local when MCP server is talking to a locally installed software, e.g. taking control over Chrome browser.
> * Use cloud when MCP server is talking to remote APIs, e.g. weather API.

## Server Implementations

> \[!NOTE]
> We now have a [web-based directory](https://glama.ai/mcp/servers) that is synced with the repository.

* 🔗 - [Aggregators](#aggregators)
* 🎨 - [Art & Culture](#art-and-culture)
* 📂 - [Browser Automation](#browser-automation)
* 🧬 - [Biology Medicine and Bioinformatics](#bio)
* ☁️ - [Cloud Platforms](#cloud-platforms)
* 👨‍💻 - [Code Execution](#code-execution)
* 🤖 - [Coding Agents](#coding-agents)
* 🖥️ - [Command Line](#command-line)
* 💬 - [Communication](#communication)
* 👤 - [Customer Data Platforms](#customer-data-platforms)
* 🗄️ - [Databases](#databases)
* 📊 - [Data Platforms](#data-platforms)
* 🚚 - [Delivery](#delivery)
* 🛠️ - [Developer Tools](#developer-tools)
* 🧮 - [Data Science Tools](#data-science-tools)
* 📟 - [Embedded system](#embedded-system)
* 📂 - [File Systems](#file-systems)
* 💰 - [Finance & Fintech](#finance--fintech)
* 🎮 - [Gaming](#gaming)
* 🧠 - [Knowledge & Memory](#knowledge--memory)
* 🗺️ - [Location Services](#location-services)
* 🎯 - [Marketing](#marketing)
* 📊 - [Monitoring](#monitoring)
* 🎥 - [Multimedia Process](#multimedia-process)
* 🔎 - [Search & Data Extraction](#search)
* 🔒 - [Security](#security)
* 🌐 - [Social Media](#social-media)
* 🏃 - [Sports](#sports)
* 🎧 - [Support & Service Management](#support-and-service-management)
* 🌎 - [Translation Services](#translation-services)
* 🎧 - [Text-to-Speech](#text-to-speech)
* 🚆 - [Travel & Transportation](#travel-and-transportation)
* 🔄 - [Version Control](#version-control)
* 🏢 - [Workplace & Productivity](#workplace-and-productivity)
* 🛠️ - [Other Tools and Integrations](#other-tools-and-integrations)

### 🔗 <a name="aggregators"></a>Aggregators

Servers for accessing many apps and tools through a single MCP server.

* [mindsdb/mindsdb](https://github.com/mindsdb/mindsdb) ⭐ 36,523 | 🐛 169 | 🌐 Python | 📅 2025-10-23 - Connect and unify data across various platforms and databases with [MindsDB as a single MCP server](https://docs.mindsdb.com/mcp/overview).
* [PipedreamHQ/pipedream](https://github.com/PipedreamHQ/pipedream/tree/master/modelcontextprotocol) ⭐ 10,721 | 🐛 4,293 | 🌐 JavaScript | 📅 2025-10-24 ☁️ 🏠 - Connect with 2,500 APIs with 8,000+ prebuilt tools, and manage servers for your users, in your own app.
* [metatool-ai/metatool-app](https://github.com/metatool-ai/metatool-app) ⭐ 1,534 | 🐛 31 | 🌐 TypeScript | 📅 2025-10-07 📇 ☁️ 🏠 🍎 🪟 🐧 - MetaMCP is the one unified middleware MCP server that manages your MCP connections with GUI.
* [julien040/anyquery](https://github.com/julien040/anyquery) ⭐ 1,468 | 🐛 6 | 🌐 Go | 📅 2025-10-02 🏎️ 🏠 ☁️ - Query more than 40 apps with one binary using SQL. It can also connect to your PostgreSQL, MySQL, or SQLite compatible database. Local-first and private by design.
* [duaraghav8/MCPJungle](https://github.com/duaraghav8/MCPJungle) ⭐ 635 | 🐛 42 | 🌐 Go | 📅 2025-10-23 🏎️ 🏠 - Self-hosted MCP Server registry for enterprise AI Agents
* [TheLunarCompany/lunar#mcpx](https://github.com/TheLunarCompany/lunar/tree/main/mcpx) ⭐ 311 | 🐛 5 | 🌐 Go | 📅 2025-10-23 📇 🏠  ☁️ 🍎 🪟 🐧 - MCPX is a production-ready, open-source gateway to manage MCP servers at scale—centralize tool discovery, access controls, call prioritization, and usage tracking to simplify agent workflows.
* [wegotdocs/open-mcp](https://github.com/wegotdocs/open-mcp) ⭐ 291 | 🐛 228 | 🌐 TypeScript | 📅 2025-09-15 📇 🏠 🍎 🪟 🐧 - Turn a web API into an MCP server in 10 seconds and add it to the open source registry: <https://open-mcp.org>
* [1mcp/agent](https://github.com/1mcp-app/agent) ⭐ 241 | 🐛 5 | 🌐 TypeScript | 📅 2025-10-23 📇 ☁️ 🏠 🍎 🪟 🐧 - A unified Model Context Protocol server implementation that aggregates multiple MCP servers into one.
* [sxhxliang/mcp-access-point](https://github.com/sxhxliang/mcp-access-point) ⭐ 135 | 🐛 1 | 🌐 Rust | 📅 2025-10-01 📇 ☁️ 🏠 🍎 🪟 🐧 - Turn a web service into an MCP server in one click without making any code changes.
* [VeriTeknik/pluggedin-mcp-proxy](https://github.com/VeriTeknik/pluggedin-mcp-proxy) ⭐ 98 | 🐛 1 | 🌐 TypeScript | 📅 2025-10-17  📇 🏠 - A comprehensive proxy server that combines multiple MCP servers into a single interface with extensive visibility features. It provides discovery and management of tools, prompts, resources, and templates across servers, plus a playground for debugging when building MCP servers.
* [sitbon/magg](https://github.com/sitbon/magg) ⭐ 97 | 🐛 3 | 🌐 Python | 📅 2025-08-07 🍎 🪟 🐧 ☁️ 🏠 🐍 - Magg: A meta-MCP server that acts as a universal hub, allowing LLMs to autonomously discover, install, and orchestrate multiple MCP servers - essentially giving AI assistants the power to extend their own capabilities on-demand.
* [SureScaleAI/openai-gpt-image-mcp](https://github.com/SureScaleAI/openai-gpt-image-mcp) ⭐ 76 | 🐛 1 | 🌐 TypeScript | 📅 2025-05-31 📇 ☁️ - OpenAI GPT image generation/editing MCP server.
* [tigranbs/mcgravity](https://github.com/tigranbs/mcgravity) ⭐ 72 | 🐛 2 | 🌐 TypeScript | 📅 2025-04-18 📇 🏠 - A proxy tool for composing multiple MCP servers into one unified endpoint. Scale your AI tools by load balancing requests across multiple MCP servers, similar to how Nginx works for web servers.
* [hamflx/imagen3-mcp](https://github.com/hamflx/imagen3-mcp) ⭐ 47 | 🐛 5 | 🌐 Rust | 📅 2025-05-03 📇 🏠 🪟 🍎 🐧 - A powerful image generation tool using Google's Imagen 3.0 API through MCP. Generate high-quality images from text prompts with advanced photography, artistic, and photorealistic controls.
* [WayStation-ai/mcp](https://github.com/waystation-ai/mcp) ⭐ 34 | 🐛 2 | 🌐 JavaScript | 📅 2025-09-10 ☁️ 🍎 🪟 - Seamlessly and securely connect Claude Desktop and other MCP hosts to your favorite apps (Notion, Slack, Monday, Airtable, etc.). Takes less than 90 secs.
* [glenngillen/mcpmcp-server](https://github.com/glenngillen/mcpmcp-server) ⭐ 21 | 🐛 0 | 📅 2025-04-24 ☁️ 📇 🍎 🪟 🐧 - A list of MCP servers so you can ask your client which servers you can use to improve your daily workflow.
* [YangLiangwei/PersonalizationMCP](https://github.com/YangLiangwei/PersonalizationMCP) ⭐ 18 | 🐛 0 | 🌐 Python | 📅 2025-09-17 🐍 ☁️ 🏠 🍎 🪟 🐧 - Comprehensive personal data aggregation MCP server with Steam, YouTube, Bilibili, Spotify, Reddit and other platforms integrations. Features OAuth2 authentication, automatic token management, and 90+ tools for gaming, music, video, and social platform data access.
* [Data-Everything/mcp-server-templates](https://github.com/Data-Everything/mcp-server-templates) ⭐ 7 | 🐛 3 | 🌐 Python | 📅 2025-08-29 📇 🏠 🍎 🪟 🐧 - One server. All tools. A unified MCP platform that connects many apps, tools, and services behind one powerful interface—ideal for local devs or production agents.
* [particlefuture/MCPDiscovery](https://github.com/particlefuture/MCPDiscovery) - MCP of MCPs. A central hub for MCP servers. Helps you discover available MCP servers and learn how to install and use them.

### 🚀 <a name="aerospace-and-astrodynamics"></a>Aerospace & Astrodynamics

* [IO-Aerospace-software-community/mcp-server](https://github.com/IO-Aerospace-software-engineering/mcp-server) ⭐ 9 | 🐛 0 | 🌐 C# | 📅 2025-10-20 #️⃣ ☁️/🏠 🐧 - IO Aerospace MCP Server: a .NET-based MCP server for aerospace & astrodynamics — ephemeris, orbital conversions, DSS tools, time conversions, and unit/math utilities. Supports STDIO and SSE transports; Docker and native .NET deployment documented.

### 🎨 <a name="art-and-culture"></a>Art & Culture

Access and explore art collections, cultural heritage, and museum databases. Enables AI models to search and analyze artistic and cultural content.

* [ahujasid/blender-mcp](https://github.com/ahujasid/blender-mcp) ⭐ 13,911 | 🐛 32 | 🌐 Python | 📅 2025-10-20 🐍 - MCP server for working with Blender
* [abhiemj/manim-mcp-server](https://github.com/abhiemj/manim-mcp-server) ⭐ 492 | 🐛 5 | 🌐 Python | 📅 2025-05-19 🐍 🏠 🪟 🐧 - A local MCP server that generates animations using Manim.
* [samuelgursky/davinci-resolve-mcp](https://github.com/samuelgursky/davinci-resolve-mcp) ⭐ 329 | 🐛 10 | 🌐 Python | 📅 2025-10-20 🐍 - MCP server integration for DaVinci Resolve providing powerful tools for video editing, color grading, media management, and project control
* [burningion/video-editing-mcp](https://github.com/burningion/video-editing-mcp) ⭐ 218 | 🐛 5 | 🌐 Python | 📅 2025-10-09 🐍 - Add, Analyze, Search, and Generate Video Edits from your Video Jungle Collection
* [cantian-ai/bazi-mcp](https://github.com/cantian-ai/bazi-mcp) ⭐ 187 | 🐛 2 | 🌐 TypeScript | 📅 2025-10-11 📇 🏠 ☁️ 🍎 🪟 - Provides comprehensive and accurate Bazi (Chinese Astrology) charting and analysis
* [diivi/aseprite-mcp](https://github.com/diivi/aseprite-mcp) ⭐ 91 | 🐛 3 | 🌐 Python | 📅 2025-09-02 🐍 🏠 - MCP server using the Aseprite API to create pixel art
* [omni-mcp/isaac-sim-mcp](https://github.com/omni-mcp/isaac-sim-mcp) ⭐ 84 | 🐛 4 | 🌐 Python | 📅 2025-04-25 📇 ☁️ - A MCP Server and an extension enables natural language control of NVIDIA Isaac Sim, Lab, OpenUSD and etc.
* [cswkim/discogs-mcp-server](https://github.com/cswkim/discogs-mcp-server) ⭐ 59 | 🐛 0 | 🌐 TypeScript | 📅 2025-10-21 📇 ☁️ - MCP server to interact with the Discogs API
* [r-huijts/rijksmuseum-mcp](https://github.com/r-huijts/rijksmuseum-mcp) ⭐ 59 | 🐛 3 | 🌐 JavaScript | 📅 2025-02-07 📇 ☁️ - Rijksmuseum API integration for artwork search, details, and collections
* [yuna0x0/anilist-mcp](https://github.com/yuna0x0/anilist-mcp) ⭐ 58 | 🐛 1 | 🌐 TypeScript | 📅 2025-10-20 📇 ☁️ - A MCP server integrating AniList API for anime and manga information
* [djalal/quran-mcp-server](https://github.com/djalal/quran-mcp-server) ⭐ 50 | 🐛 6 | 🌐 TypeScript | 📅 2025-06-12 📇 ☁️ MCP server to interact with Quran.com corpus via the official REST API v4.
* [8enSmith/mcp-open-library](https://github.com/8enSmith/mcp-open-library) ⭐ 42 | 🐛 0 | 🌐 TypeScript | 📅 2025-09-06 📇 ☁️ - A MCP server for the Open Library API that enables AI assistants to search for book information.
* [PatrickPalmer/MayaMCP](https://github.com/PatrickPalmer/MayaMCP) ⭐ 27 | 🐛 3 | 🌐 Python | 📅 2025-05-12 🐍 🏠 - MCP server for Autodesk Maya
* [OctoEverywhere/mcp](https://github.com/OctoEverywhere/mcp) ⭐ 17 | 🐛 0 | 📅 2025-07-03 #️⃣ ☁️ - A 3D printer MCP server that allows for getting live printer state, webcam snapshots, and printer control.
* [mikechao/metmuseum-mcp](https://github.com/mikechao/metmuseum-mcp) ⭐ 15 | 🐛 0 | 🌐 TypeScript | 📅 2025-07-17 📇 ☁️ - Metropolitan Museum of Art Collection API integration to search and display artworks in the collection.
* [r-huijts/oorlogsbronnen-mcp](https://github.com/r-huijts/oorlogsbronnen-mcp) ⭐ 12 | 🐛 3 | 🌐 TypeScript | 📅 2025-05-23 📇 ☁️ - Oorlogsbronnen (War Sources) API integration for accessing historical WWII records, photographs, and documents from the Netherlands (1940-1945)
* [raveenb/fal-mcp-server](https://github.com/raveenb/fal-mcp-server) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2025-09-02 🐍 ☁️ - Generate AI images, videos, and music using Fal.ai models (FLUX, Stable Diffusion, MusicGen) directly in Claude Desktop
* [drakonkat/wizzy-mcp-tmdb](https://github.com/drakonkat/wizzy-mcp-tmdb) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2025-09-30 📇 ☁️ - A MCP server for The Movie Database API that enables AI assistants to search and retrieve movie, TV show, and person information.
* [peek-travel/mcp-intro](https://github.com/peek-travel/mcp-intro) ⭐ 0 | 🐛 0 | 📅 2025-09-23 ☁️ 🍎 🪟 🐧 - Remote MCP Server for discovering and planning experiences, at home and on vacation

### <a name="bio"></a>Biology, Medicine and Bioinformatics

* [genomoncology/biomcp](https://github.com/genomoncology/biomcp) ⭐ 327 | 🐛 1 | 🌐 Python | 📅 2025-10-23 🐍 ☁️ - Biomedical research MCP server providing access to PubMed, ClinicalTrials.gov, and MyVariant.info.
* [the-momentum/apple-health-mcp-server](https://github.com/the-momentum/apple-health-mcp-server) ⭐ 59 | 🐛 7 | 🌐 Python | 📅 2025-10-22 🐍 🏠 🍎 🪟 🐧 - An MCP server that provides access to exported data from Apple Health. Data analytics included.
* [wso2/fhir-mcp-server](https://github.com/wso2/fhir-mcp-server) ⭐ 56 | 🐛 2 | 🌐 Python | 📅 2025-10-23 🐍 🏠 ☁️ - Model Context Protocol server for Fast Healthcare Interoperability Resources (FHIR) APIs. Provides seamless integration with FHIR servers, enabling AI assistants to search, retrieve, create, update, and analyze clinical healthcare data with SMART-on-FHIR authentication support.
* [the-momentum/fhir-mcp-server](https://github.com/the-momentum/fhir-mcp-server) ⭐ 31 | 🐛 6 | 🌐 Python | 📅 2025-10-23 🐍 🏠 ☁️ - MCP Server that connects AI agents to FHIR servers. One example use case is querying patient history in natural language.
* [JamesANZ/medical-mcp](https://github.com/JamesANZ/medical-mcp) ⭐ 26 | 🐛 2 | 🌐 TypeScript | 📅 2025-10-19 📇 🏠 - An MCP server that provides access to medical information, drug databases, and healthcare resources. Enables AI assistants to query medical data, drug interactions, and clinical guidelines.
* [longevity-genie/biothings-mcp](https://github.com/longevity-genie/biothings-mcp) ⭐ 25 | 🐛 1 | 🌐 Python | 📅 2025-07-20 🐍 🏠 ☁️ - MCP server to interact with the BioThings API, including genes, genetic variants, drugs, and taxonomic information.
* [longevity-genie/gget-mcp](https://github.com/longevity-genie/gget-mcp) ⭐ 17 | 🐛 5 | 🌐 Python | 📅 2025-10-13 🐍 🏠 ☁️ - MCP server providing a powerful bioinformatics toolkit for genomics queries and analysis, wrapping the popular `gget` library.
* [OHNLP/omop\_mcp](https://github.com/OHNLP/omop_mcp) ⭐ 15 | 🐛 1 | 🌐 Python | 📅 2025-10-17 🐍 🏠 ☁️ - Map clinical terminology to OMOP concepts using LLMs for healthcare data standardization and interoperability.
* [longevity-genie/opengenes-mcp](https://github.com/longevity-genie/opengenes-mcp) ⭐ 12 | 🐛 1 | 🌐 Python | 📅 2025-10-14 🎖️ 🐍 🏠 ☁️ - MCP server for a queryable database for aging and longevity research from the OpenGenes project.
* [longevity-genie/synergy-age-mcp](https://github.com/longevity-genie/synergy-age-mcp) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2025-08-25 🎖️ 🐍 🏠 ☁️ - MCP server for the SynergyAge database of synergistic and antagonistic genetic interactions in longevity.

### 📂 <a name="browser-automation"></a>Browser Automation

Web content access and automation capabilities. Enables searching, scraping, and processing web content in AI-friendly formats.

* [modelcontextprotocol/server-puppeteer](https://github.com/modelcontextprotocol/servers/tree/main/src/puppeteer) ⭐ 71,117 | 🐛 277 | 🌐 TypeScript | 📅 2025-10-24 📇 🏠 - Browser automation for web scraping and interaction
* [microsoft/playwright-mcp](https://github.com/microsoft/playwright-mcp) ⭐ 22,326 | 🐛 31 | 🌐 TypeScript | 📅 2025-10-22 - Official Microsoft Playwright MCP server, enabling LLMs to interact with web pages through structured accessibility snapshots
* [agent-infra/mcp-server-browser](https://github.com/bytedance/UI-TARS-desktop/tree/main/packages/agent-infra/mcp-servers/browser) ⭐ 19,270 | 🐛 299 | 🌐 TypeScript | 📅 2025-10-16 📇 🏠 - Browser automation capabilities using Puppeteer, both support local and remote browser connection.
* [executeautomation/playwright-mcp-server](https://github.com/executeautomation/mcp-playwright) ⭐ 4,931 | 🐛 51 | 🌐 TypeScript | 📅 2025-06-20 📇 - An MCP server using Playwright for browser automation and webscrapping
* [browsermcp/mcp](https://github.com/browsermcp/mcp) ⭐ 4,704 | 🐛 96 | 🌐 TypeScript | 📅 2025-04-24 📇 🏠 - Automate your local Chrome browser
* [browserbase/mcp-server-browserbase](https://github.com/browserbase/mcp-server-browserbase) ⭐ 2,747 | 🐛 19 | 🌐 TypeScript | 📅 2025-10-16 🎖️ 📇 - Automate browser interactions in the cloud (e.g. web navigation, data extraction, form filling, and more)
* [operative\_sh/web-eval-agent](https://github.com/Operative-Sh/web-eval-agent) ⭐ 1,196 | 🐛 11 | 🌐 Python | 📅 2025-10-08 🐍 🏠 🍎 - An MCP Server that autonomously debugs web applications with browser-use browser agents
* [co-browser/browser-use-mcp-server](https://github.com/co-browser/browser-use-mcp-server) ⭐ 761 | 🐛 14 | 🌐 Python | 📅 2025-07-10 🐍 - browser-use packaged as an MCP server with SSE transport. includes a dockerfile to run chromium in docker + a vnc server.
* [kimtaeyoon83/mcp-server-youtube-transcript](https://github.com/kimtaeyoon83/mcp-server-youtube-transcript) ⭐ 335 | 🐛 9 | 🌐 JavaScript | 📅 2025-08-08 📇 ☁️ - Fetch YouTube subtitles and transcripts for AI analysis
* [eat-pray-ai/yutu](https://github.com/eat-pray-ai/yutu) ⭐ 327 | 🐛 3 | 🌐 Go | 📅 2025-10-21 🏎️ 🏠 🍎 🐧 🪟 - A fully functional MCP server and CLI for YouTube to automate YouTube operation
* [pskill9/web-search](https://github.com/pskill9/web-search) ⭐ 315 | 🐛 7 | 🌐 JavaScript | 📅 2024-12-30 📇 🏠 - An MCP server that enables free web searching using Google search results, with no API keys required.
* [automatalabs/mcp-server-playwright](https://github.com/Automata-Labs-team/MCP-Server-Playwright) ⭐ 262 | 🐛 9 | 🌐 JavaScript | 📅 2025-06-05 🐍 - An MCP server for browser automation using Playwright
* [recursechat/mcp-server-apple-shortcuts](https://github.com/recursechat/mcp-server-apple-shortcuts) ⭐ 248 | 🐛 4 | 🌐 JavaScript | 📅 2024-12-22 📇 🏠 🍎 - An MCP Server Integration with Apple Shortcuts
* [eyalzh/browser-control-mcp](https://github.com/eyalzh/browser-control-mcp) ⭐ 187 | 🐛 11 | 🌐 TypeScript | 📅 2025-09-05 📇 🏠 - An MCP server paired with a browser extension that enables LLM clients to control the user's browser (Firefox).
* [blackwhite084/playwright-plus-python-mcp](https://github.com/blackwhite084/playwright-plus-python-mcp) ⭐ 157 | 🐛 5 | 🌐 Python | 📅 2025-01-07 🐍 - An MCP python server using Playwright for browser automation,more suitable for llm
* [34892002/bilibili-mcp-js](https://github.com/34892002/bilibili-mcp-js) ⭐ 122 | 🐛 4 | 🌐 TypeScript | 📅 2025-04-23 📇 🏠 - A MCP server that supports searching for Bilibili content. Provides LangChain integration examples and test scripts.
* [fradser/mcp-server-apple-reminders](https://github.com/FradSer/mcp-server-apple-reminders) ⭐ 120 | 🐛 5 | 🌐 TypeScript | 📅 2025-10-10 📇 🏠 🍎 - An MCP server for interacting with Apple Reminders on macOS
* [getrupt/ashra-mcp](https://github.com/getrupt/ashra-mcp) ⭐ 45 | 🐛 2 | 🌐 TypeScript | 📅 2025-03-26 📇 🏠 - Extract structured data from any website. Just prompt and get JSON.
* [ndthanhdev/mcp-browser-kit](https://github.com/ndthanhdev/mcp-browser-kit) ⭐ 38 | 🐛 1 | 🌐 TypeScript | 📅 2025-10-21 📇 🏠 - An MCP Server that enables AI assistants to interact with your local browsers.
* [lightpanda-io/gomcp](https://github.com/lightpanda-io/gomcp) ⭐ 35 | 🐛 3 | 🌐 Go | 📅 2025-06-23 🏎 🏠/☁️ 🐧/🍎 - An MCP server in Go for Lightpanda, the ultra fast headless browser designed for web automation
* [kimtth/mcp-aoai-web-browsing](https://github.com/kimtth/mcp-aoai-web-browsing) ⭐ 30 | 🐛 2 | 🌐 Python | 📅 2025-04-07 🐍 🏠 - A `minimal` server/client MCP implementation using Azure OpenAI and Playwright.
* [imprvhub/mcp-browser-agent](https://github.com/imprvhub/mcp-browser-agent) ⭐ 26 | 🐛 2 | 🌐 TypeScript | 📅 2025-10-22 📇 🏠 - A Model Context Protocol (MCP) integration that provides Claude Desktop with autonomous browser automation capabilities.
* [xspadex/bilibili-mcp](https://github.com/xspadex/bilibili-mcp.git) ⭐ 13 | 🐛 1 | 🌐 Python | 📅 2025-04-23 📇 🏠 - A FastMCP-based tool that fetches Bilibili's trending videos and exposes them via a standard MCP interface.
* [PhungXuanAnh/selenium-mcp-server](https://github.com/PhungXuanAnh/selenium-mcp-server) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2025-10-04 🐍 🏠 🍎 🪟 🐧 - A Model Context Protocol server providing web automation capabilities through Selenium WebDriver
* [freema/firefox-devtools-mcp](https://github.com/freema/firefox-devtools-mcp) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2025-10-19 📇 🏠 - Firefox browser automation via WebDriver BiDi for testing, scraping, and browser control. Supports snapshot/UID-based interactions, network monitoring, console capture, and screenshots.

### ☁️ <a name="cloud-platforms"></a>Cloud Platforms

Cloud platform service integration. Enables management and interaction with cloud infrastructure and services.

* [awslabs/mcp](https://github.com/awslabs/mcp) ⭐ 6,825 | 🐛 228 | 🌐 Python | 📅 2025-10-23 🎖️ ☁️ - AWS MCP servers for seamless integration with AWS services and resources.
* [cloudflare/mcp-server-cloudflare](https://github.com/cloudflare/mcp-server-cloudflare) ⭐ 3,049 | 🐛 35 | 🌐 TypeScript | 📅 2025-10-16 🎖️ 📇 ☁️ - Integration with Cloudflare services including Workers, KV, R2, and D1
* [flux159/mcp-server-kubernetes](https://github.com/Flux159/mcp-server-kubernetes) ⭐ 1,159 | 🐛 17 | 🌐 TypeScript | 📅 2025-10-21 📇 ☁️/🏠 - Typescript implementation of Kubernetes cluster operations for pods, deployments, services.
* [rohitg00/kubectl-mcp-server](https://github.com/rohitg00/kubectl-mcp-server) ⭐ 732 | 🐛 14 | 🌐 Python | 📅 2025-07-14 🐍 ☁️/🏠 - A Model Context Protocol (MCP) server for Kubernetes that enables AI assistants like Claude, Cursor, and others to interact with Kubernetes clusters through natural language.
* [manusa/Kubernetes MCP Server](https://github.com/manusa/kubernetes-mcp-server) ⭐ 728 | 🐛 37 | 🌐 Go | 📅 2025-10-23 🏎️ 🏠 A - powerful Kubernetes MCP server with additional support for OpenShift. Besides providing CRUD operations for **any** Kubernetes resource, this server provides specialized tools to interact with your cluster.
* [weibaohui/k8m](https://github.com/weibaohui/k8m) ⭐ 687 | 🐛 16 | 🌐 Go | 📅 2025-10-24 🏎️ ☁️/🏠 - Provides MCP multi-cluster Kubernetes management and operations, featuring a management interface, logging, and nearly 50 built-in tools covering common DevOps and development scenarios. Supports both standard and CRD resources.
* [strowk/mcp-k8s-go](https://github.com/strowk/mcp-k8s-go) ⭐ 353 | 🐛 10 | 🌐 Go | 📅 2025-09-15 🏎️ ☁️/🏠 - Kubernetes cluster operations through MCP
* [nwiizo/tfmcp](https://github.com/nwiizo/tfmcp) ⭐ 343 | 🐛 4 | 🌐 Rust | 📅 2025-06-14 - 🦀 🏠 - A Terraform MCP server allowing AI assistants to manage and operate Terraform environments, enabling reading configurations, analyzing plans, applying configurations, and managing Terraform state.
* [alexei-led/k8s-mcp-server](https://github.com/alexei-led/k8s-mcp-server) ⭐ 169 | 🐛 4 | 🌐 Python | 📅 2025-04-29 🐍 - A lightweight yet robust server that empowers AI assistants to securely execute Kubernetes CLI commands (`kubectl`, `helm`, `istioctl`, and `argocd`) using Unix pipes in a safe Docker environment with multi-architecture support.
* [alexei-led/aws-mcp-server](https://github.com/alexei-led/aws-mcp-server) ⭐ 164 | 🐛 8 | 🌐 Python | 📅 2025-04-10 🐍 ☁️ - A lightweight but powerful server that enables AI assistants to execute AWS CLI commands, use Unix pipes, and apply prompt templates for common AWS tasks in a safe Docker environment with multi-architecture support
* [weibaohui/kom](https://github.com/weibaohui/kom) ⭐ 131 | 🐛 3 | 🌐 Go | 📅 2025-10-22 🏎️ ☁️/🏠 - Provides MCP multi-cluster Kubernetes management and operations. It can be integrated as an SDK into your own project and includes nearly 50 built-in tools covering common DevOps and development scenarios. Supports both standard and CRD resources.
* [silenceper/mcp-k8s](https://github.com/silenceper/mcp-k8s) ⭐ 129 | 🐛 1 | 🌐 Go | 📅 2025-08-15 🏎️ ☁️/🏠 - MCP-K8S is an AI-driven Kubernetes resource management tool that allows users to operate any resources in Kubernetes clusters through natural language interaction, including native resources (like Deployment, Service) and custom resources (CRD). No need to memorize complex commands - just describe your needs, and AI will accurately execute the corresponding cluster operations, greatly enhancing the usability of Kubernetes.
* [reza-gholizade/k8s-mcp-server](https://github.com/reza-gholizade/k8s-mcp-server) ⭐ 112 | 🐛 1 | 🌐 Go | 📅 2025-10-14 🏎️ ☁️/🏠 - A Kubernetes Model Context Protocol (MCP) server that provides tools for interacting with Kubernetes clusters through a standardized interface, including API resource discovery, resource management, pod logs, metrics, and events.
* [aliyun/alibaba-cloud-ops-mcp-server](https://github.com/aliyun/alibaba-cloud-ops-mcp-server) ⭐ 78 | 🐛 6 | 🌐 Python | 📅 2025-10-11 🎖️ 🐍 ☁️ - A MCP server that enables AI assistants to operation resources on Alibaba Cloud, supporting ECS, Cloud Monitor, OOS and widely used cloud products.
* [portainer/portainer-mcp](https://github.com/portainer/portainer-mcp) ⭐ 74 | 🐛 6 | 🌐 Go | 📅 2025-06-30 🏎️ ☁️/🏠 - A powerful MCP server that enables AI assistants to seamlessly interact with Portainer instances, providing natural language access to container management, deployment operations, and infrastructure monitoring capabilities.
* [StacklokLabs/mkp](https://github.com/StacklokLabs/mkp) ⭐ 54 | 🐛 6 | 🌐 Go | 📅 2025-10-22 🏎️ ☁️ - MKP is a Model Context Protocol (MCP) server for Kubernetes that allows LLM-powered applications to interact with Kubernetes clusters. It provides tools for listing and applying Kubernetes resources through the MCP protocol.
* [bright8192/esxi-mcp-server](https://github.com/bright8192/esxi-mcp-server) ⭐ 41 | 🐛 6 | 🌐 Python | 📅 2025-07-01 🐍 ☁️ - A VMware ESXi/vCenter management server based on MCP (Model Control Protocol), providing simple REST API interfaces for virtual machine management.
* [redis/mcp-redis-cloud](https://github.com/redis/mcp-redis-cloud) ⭐ 37 | 🐛 1 | 🌐 TypeScript | 📅 2025-05-05 📇 ☁️ - Manage your Redis Cloud resources effortlessly using natural language. Create databases, monitor subscriptions, and configure cloud deployments with simple commands.
* [cyclops-ui/mcp-cyclops](https://github.com/cyclops-ui/mcp-cyclops) ⭐ 29 | 🐛 2 | 🌐 Go | 📅 2025-06-25 🎖️ 🏎️ ☁️ - An MCP server that allows AI agents to manage Kubernetes resources through Cyclops abstraction
* [qiniu/qiniu-mcp-server](https://github.com/qiniu/qiniu-mcp-server) ⭐ 29 | 🐛 2 | 🌐 Python | 📅 2025-06-27 🐍 ☁️ - A MCP built on Qiniu Cloud products, supporting access to Qiniu Cloud Storage, media processing services, etc.
* [wenhuwang/mcp-k8s-eye](https://github.com/wenhuwang/mcp-k8s-eye) ⭐ 24 | 🐛 1 | 🌐 Go | 📅 2025-05-16 🏎️ ☁️/🏠 - MCP Server for kubernetes management, and analyze your cluster, application health
* [pibblokto/cert-manager-mcp-server](https://github.com/pibblokto/cert-manager-mcp-server) ⭐ 16 | 🐛 0 | 🌐 Python | 📅 2025-08-25 🐍 🍎/🐧 ☁️ - mcp server for [cert-manager](https://github.com/cert-manager/cert-manager) ⭐ 13,245 | 🐛 208 | 🌐 Go | 📅 2025-10-24 management and troubleshooting
* [trilogy-group/aws-pricing-mcp](https://github.com/trilogy-group/aws-pricing-mcp) ⭐ 16 | 🐛 3 | 🌐 Python | 📅 2025-07-24 🏎️ ☁️/🏠 - Get up-to-date EC2 pricing information with one call. Fast. Powered by a pre-parsed AWS pricing catalogue.
* [kestra-io/mcp-server-python](https://github.com/kestra-io/mcp-server-python) ⭐ 14 | 🐛 2 | 🌐 Python | 📅 2025-09-09 🐍 ☁️ - Implementation of MCP server for [Kestra](https://kestra.io) workflow orchestration platform.
* [openstack-kr/python-openstackmcp-server](https://github.com/openstack-kr/python-openstackmcp-server) ⭐ 14 | 🐛 10 | 🌐 Python | 📅 2025-10-24 🐍 ☁️ - OpenStack MCP server for cloud infrastructure management based on openstacksdk.
* [hardik-id/azure-resource-graph-mcp-server](https://github.com/hardik-id/azure-resource-graph-mcp-server) ⭐ 12 | 🐛 1 | 🌐 TypeScript | 📅 2025-05-06 📇 ☁️/🏠 - A Model Context Protocol server for querying and analyzing Azure resources at scale using Azure Resource Graph, enabling AI assistants to explore and monitor Azure infrastructure.
* [alexbakers/mcp-ipfs](https://github.com/alexbakers/mcp-ipfs) ⭐ 11 | 🐛 3 | 🌐 TypeScript | 📅 2025-04-10 📇 ☁️ - upload and manipulation of IPFS storage
* [liveblocks/liveblocks-mcp-server](https://github.com/liveblocks/liveblocks-mcp-server) ⭐ 11 | 🐛 4 | 🌐 TypeScript | 📅 2025-05-01 🎖️ 📇 ☁️ - Create, modify, and delete different aspects of [Liveblocks](https://liveblocks.io) such as rooms, threads, comments, notifications, and more. Additionally, it has read access to Storage and Yjs.
* [StacklokLabs/ocireg-mcp](https://github.com/StacklokLabs/ocireg-mcp) ⭐ 11 | 🐛 3 | 🌐 Go | 📅 2025-10-21 🏎️ ☁️ - An SSE-based MCP server that allows LLM-powered applications to interact with OCI registries. It provides tools for retrieving information about container images, listing tags, and more.
* [thunderboltsid/mcp-nutanix](https://github.com/thunderboltsid/mcp-nutanix) ⭐ 11 | 🐛 1 | 🌐 Go | 📅 2025-08-13 🏎️ 🏠/☁️ - Go-based MCP Server for interfacing with Nutanix Prism Central resources.
* [espressif/esp-rainmaker-mcp](https://github.com/espressif/esp-rainmaker-mcp) ⭐ 9 | 🐛 1 | 🌐 Python | 📅 2025-07-15 🎖️ 🐍 🏠 ☁️ 📟 - Official Espressif MCP Server to manage and control ESP RainMaker Devices.
* [pythonanywhere/pythonanywhere-mcp-server](https://github.com/pythonanywhere/pythonanywhere-mcp-server) ⭐ 8 | 🐛 4 | 🌐 Python | 📅 2025-10-20 🐍 🏠 - MCP server implementation for PythonAnywhere cloud platform.
* [aashari/mcp-server-aws-sso](https://github.com/aashari/mcp-server-aws-sso) ⭐ 6 | 🐛 15 | 🌐 TypeScript | 📅 2025-10-20 📇 ☁️ 🏠 - AWS Single Sign-On (SSO) integration enabling AI systems to securely interact with AWS resources by initiating SSO login, listing accounts/roles, and executing AWS CLI commands using temporary credentials.
* [VmLia/books-mcp-server](https://github.com/VmLia/books-mcp-server) ⭐ 5 | 🐛 1 | 🌐 Python | 📅 2025-04-09 📇 ☁️ - This is an MCP server used for querying books, and it can be applied in common MCP clients, such as Cherry Studio.
* [erikhoward/adls-mcp-server](https://github.com/erikhoward/adls-mcp-server) ⭐ 4 | 🐛 3 | 🌐 Python | 📅 2025-05-31 🐍 ☁️/🏠 - MCP Server for Azure Data Lake Storage. It can perform manage containers, read/write/upload/download operations on container files and manage file metadata.
* [johnneerdael/netskope-mcp](https://github.com/johnneerdael/netskope-mcp) ⭐ 3 | 🐛 1 | 🌐 TypeScript | 📅 2025-08-08 🔒 ☁️ - An MCP to give access to all Netskope Private Access components within a Netskope Private Access environments including detailed setup information and LLM examples on usage.
* [4everland/4everland-hosting-mcp](https://github.com/4everland/4everland-hosting-mcp) ⭐ 1 | 🐛 2 | 🌐 TypeScript | 📅 2025-06-19 🎖️ 📇 🏠 🍎 🐧 - An MCP server implementation for 4EVERLAND Hosting enabling instant deployment of AI-generated code to decentralized storage networks like Greenfield, IPFS, and Arweave.
* [Nebula-Block-Data/nebulablock-mcp-server](https://github.com/Nebula-Block-Data/nebulablock-mcp-server) ⭐ 1 | 🐛 3 | 🌐 Python | 📅 2025-06-23 📇 🏠 - integrates with the fastmcp library to expose the full range of NebulaBlock API functionalities as accessible tools
* [elementfm/mcp](https://gitlab.com/elementfm/mcp) 🎖️ 🐍 📇 🏠 ☁️ - Open source podcast hosting platform
* [jdubois/azure-cli-mcp](https://github.com/jdubois/azure-cli-mcp) - A wrapper around the Azure CLI command line that allows you to talk directly to Azure
* [pulumi/mcp-server](https://github.com/pulumi/mcp-server) 🎖️ 📇 🏠 - MCP server for interacting with Pulumi using the Pulumi Automation API and Pulumi Cloud API. Enables MCP clients to perform Pulumi operations like retrieving package information, previewing changes, deploying updates, and retrieving stack outputs programmatically.

### 👨‍💻 <a name="code-execution"></a>Code Execution

Code execution servers. Allow LLMs to execute code in a secure environment, e.g. for coding agents.

* [pydantic/pydantic-ai/mcp-run-python](https://github.com/pydantic/pydantic-ai/tree/main/mcp-run-python) ⭐ 13,019 | 🐛 337 | 🌐 Python | 📅 2025-10-24 🐍 🏠 - Run Python code in a secure sandbox via MCP tool calls
* [dagger/container-use](https://github.com/dagger/container-use) ⭐ 3,181 | 🐛 59 | 🌐 Go | 📅 2025-10-20 🏎️ 🏠 🐧 🍎 🪟 - Containerized environments for coding agents. Multiple agents can work independently, isolated in fresh containers and git branches. No conflicts, many experiments. Full execution history, terminal access to agent environments, git workflow. Any agent/model/infra stack.
* [ckanthony/openapi-mcp](https://github.com/ckanthony/openapi-mcp) ⭐ 142 | 🐛 3 | 🌐 Go | 📅 2025-04-22 🏎️ ☁️ - OpenAPI-MCP: Dockerized MCP Server to allow your AI agent to access any API with existing api docs.
* [alfonsograziano/node-code-sandbox-mcp](https://github.com/alfonsograziano/node-code-sandbox-mcp) ⭐ 113 | 🐛 12 | 🌐 TypeScript | 📅 2025-09-06 📇 🏠 – A Node.js MCP server that spins up isolated Docker-based sandboxes for executing JavaScript snippets with on-the-fly npm dependency installation and clean teardown
* [yepcode/mcp-server-js](https://github.com/yepcode/mcp-server-js) ⭐ 36 | 🐛 1 | 🌐 TypeScript | 📅 2025-10-09 🎖️ 📇 ☁️ - Execute any LLM-generated code in a secure and scalable sandbox environment and create your own MCP tools using JavaScript or Python, with full support for NPM and PyPI packages
* [gwbischof/outsource-mcp](https://github.com/gwbischof/outsource-mcp) ⭐ 23 | 🐛 4 | 🌐 Python | 📅 2025-05-28 🐍 ☁️ - Give your AI assistant its own AI assistants. For example: "Could you ask openai to generate an image of a dog?"
* [ouvreboite/openapi-to-mcp](https://github.com/ouvreboite/openapi-to-mcp) ⭐ 21 | 🐛 4 | 🌐 C# | 📅 2025-07-15 #️⃣ ☁️ - Lightweight MCP server to access any API using their OpenAPI specification. Supports OAuth2 and full JSON schema parameters and request body.
* [r33drichards/mcp-js](https://github.com/r33drichards/mcp-js) ⭐ 20 | 🐛 3 | 🌐 Rust | 📅 2025-10-20 🦀 🏠 🐧 🍎 - A Javascript code execution sandbox that uses v8 to isolate code to run AI generated javascript locally without fear. Supports heap snapshotting for persistent sessions.
* [hileamlakB/PRIMS](https://github.com/hileamlakB/PRIMS) ⭐ 18 | 🐛 12 | 🌐 Python | 📅 2025-10-15 🐍 🏠 – A Python Runtime Interpreter MCP Server that executes user-submitted code in an isolated environment.

### 🤖 <a name="coding-agents"></a>Coding Agents

Full coding agents that enable LLMs to read, edit, and execute code and solve general programming tasks completely autonomously.

* [oraios/serena](https://github.com/oraios/serena) ⭐ 14,743 | 🐛 82 | 🌐 Python | 📅 2025-10-23 🐍 🏠 - A fully-featured coding agent that relies on symbolic code operations by using language servers.
* [ezyang/codemcp](https://github.com/ezyang/codemcp) ⭐ 1,565 | 🐛 78 | 🌐 Python | 📅 2025-06-04 🐍 🏠 - Coding agent with basic read, write and command line tools.
* [rinadelph/Agent-MCP](https://github.com/rinadelph/Agent-MCP) ⭐ 996 | 🐛 14 | 🌐 TypeScript | 📅 2025-10-09 🐍 🏠 - A framework for creating multi-agent systems using MCP for coordinated AI collaboration, featuring task management, shared context, and RAG capabilities.
* [juehang/vscode-mcp-server](https://github.com/juehang/vscode-mcp-server) ⭐ 264 | 🐛 6 | 🌐 TypeScript | 📅 2025-09-18 📇 🏠 - A MCP Server that allows AI such as Claude to read from the directory structure in a VS Code workspace, see problems picked up by linter(s) and the language server, read code files, and make edits.
* [stippi/code-assistant](https://github.com/stippi/code-assistant) ⭐ 103 | 🐛 1 | 🌐 Rust | 📅 2025-10-23 🦀 🏠 - Coding agent with basic list, read, replace\_in\_file, write, execute\_command and web search tools. Supports multiple projects concurrently.
* [tiianhk/MaxMSP-MCP-Server](https://github.com/tiianhk/MaxMSP-MCP-Server) ⭐ 101 | 🐛 8 | 🌐 Max | 📅 2025-08-27 🐍 🏠 🎵 🎥 - A coding agent for Max (Max/MSP/Jitter), which is a visual programming language for music and multimedia.
* [jinzcdev/leetcode-mcp-server](https://github.com/jinzcdev/leetcode-mcp-server) ⭐ 66 | 🐛 4 | 🌐 TypeScript | 📅 2025-05-31 📇 ☁️ - MCP server enabling automated access to **LeetCode**'s programming problems, solutions, submissions and public data with optional authentication for user-specific features (e.g., notes), supporting both `leetcode.com` (global) and `leetcode.cn` (China) sites.
* [micl2e2/code-to-tree](https://github.com/micl2e2/code-to-tree) ⭐ 60 | 🐛 1 | 🌐 C | 📅 2025-05-17 🌊 🏠 📟 🐧 🪟 🍎 - A single-binary MCP server that converts source code into AST, regardless of language.
* [nesquikm/mcp-rubber-duck](https://github.com/nesquikm/mcp-rubber-duck) ⭐ 54 | 🐛 0 | 🌐 TypeScript | 📅 2025-09-17 📇 🏠 ☁️ - An MCP server that bridges to multiple OpenAI-compatible LLMs - your AI rubber duck debugging panel for explaining problems to various AI "ducks" and getting different perspectives
* [doggybee/mcp-server-leetcode](https://github.com/doggybee/mcp-server-leetcode) ⭐ 32 | 🐛 3 | 🌐 TypeScript | 📅 2025-04-02 📇 ☁️ - An MCP server that enables AI models to search, retrieve, and solve LeetCode problems. Supports metadata filtering, user profiles, submissions, and contest data access.
* [gabrielmaialva33/winx-code-agent](https://github.com/gabrielmaialva33/winx-code-agent) ⭐ 19 | 🐛 2 | 🌐 Rust | 📅 2025-10-13 🦀 🏠 - A high-performance Rust reimplementation of WCGW for code agents, providing shell execution and advanced file management capabilities for LLMs via MCP.
* [VertexStudio/developer](https://github.com/VertexStudio/developer) ⭐ 14 | 🐛 1 | 🌐 Rust | 📅 2025-07-11 🦀 🏠 🍎 🪟 🐧 - Comprehensive developer tools for file editing, shell command execution, and screen capture capabilities
* [pdavis68/RepoMapper](https://github.com.mcas.ms/pdavis68/RepoMapper) 🐧 🪟 🍎 - An MCP server (and command-line tool) to provide a dynamic map of chat-related files from the repository with their function prototypes and related files in order of relevance. Based on the "Repo Map" functionality in Aider.chat

### 🖥️ <a name="command-line"></a>Command Line

Run commands, capture output and otherwise interact with shells and command line tools.

* [wonderwhy-er/DesktopCommanderMCP](https://github.com/wonderwhy-er/DesktopCommanderMCP) ⭐ 4,755 | 🐛 69 | 🌐 TypeScript | 📅 2025-10-22 📇 🏠 🍎 🪟 🐧 - A swiss-army-knife that can manage/execute programs and read/write/search/edit code and text files.
* [ferrislucas/iterm-mcp](https://github.com/ferrislucas/iterm-mcp) ⭐ 465 | 🐛 11 | 🌐 TypeScript | 📅 2025-09-20 🖥️ 🛠️ 💬 - A Model Context Protocol server that provides access to iTerm. You can run commands and ask questions about what you see in the iTerm terminal.
* [aymericzip/intlayer](https://github.com/aymericzip/intlayer) ⭐ 374 | 🐛 44 | 🌐 TypeScript | 📅 2025-10-24 📇 ☁️ 🏠 - A MCP Server that enhance your IDE with AI-powered assistance for Intlayer i18n / CMS tool: smart CLI access, access to the docs.
* [g0t4/mcp-server-commands](https://github.com/g0t4/mcp-server-commands) ⭐ 201 | 🐛 5 | 🌐 TypeScript | 📅 2025-09-29 📇 🏠 - Run any command with `run_command` and `run_script` tools.
* [MladenSU/cli-mcp-server](https://github.com/MladenSU/cli-mcp-server) ⭐ 150 | 🐛 5 | 🌐 Python | 📅 2025-07-04 🐍 🏠 - Command line interface with secure execution and customizable security policies
* [tumf/mcp-shell-server](https://github.com/tumf/mcp-shell-server) ⭐ 146 | 🐛 3 | 🌐 Python | 📅 2025-09-08 - A secure shell command execution server implementing the Model Context Protocol (MCP)
* [tufantunc/ssh-mcp](https://github.com/tufantunc/ssh-mcp) ⭐ 122 | 🐛 0 | 🌐 TypeScript | 📅 2025-10-21 📇 🏠 🐧 🪟 - MCP server exposing SSH control for Linux and Windows servers via Model Context Protocol. Securely execute remote shell commands with password or SSH key authentication.
* [automateyournetwork/pyATS\_MCP](https://github.com/automateyournetwork/pyATS_MCP) ⭐ 47 | 🐛 0 | 🌐 Python | 📅 2025-09-13 - Cisco pyATS server enabling structured, model-driven interaction with network devices.
* [sonirico/mcp-shell](https://github.com/sonirico/mcp-shell) ⭐ 38 | 🐛 4 | 🌐 Go | 📅 2025-09-17 - 🏎️ 🏠 🍎 🪟 🐧 Give hands to AI. MCP server to run shell commands securely, auditably, and on demand on isolated environments like docker.
* [maxim-saplin/mcp\_safe\_local\_python\_executor](https://github.com/maxim-saplin/mcp_safe_local_python_executor) ⭐ 37 | 🐛 1 | 🌐 Python | 📅 2025-07-17 - Safe Python interpreter based on HF Smolagents `LocalPythonExecutor`
* [OthmaneBlial/term\_mcp\_deepseek](https://github.com/OthmaneBlial/term_mcp_deepseek) ⭐ 12 | 🐛 0 | 🌐 Python | 📅 2025-09-21 🐍 🏠 - A DeepSeek MCP-like Server for Terminal
* [misiektoja/kill-process-mcp](https://github.com/misiektoja/kill-process-mcp) ⭐ 10 | 🐛 4 | 🌐 Python | 📅 2025-07-01 🐍 🏠 🍎 🪟 🐧 - List and terminate OS processes via natural language queries

### 💬 <a name="communication"></a>Communication

Integration with communication platforms for message management and channel operations. Enables AI models to interact with team communication tools.

* [elie222/inbox-zero](https://github.com/elie222/inbox-zero/tree/main/apps/mcp-server) ⭐ 9,136 | 🐛 80 | 🌐 TypeScript | 📅 2025-10-23 🐍 ☁️ - An MCP server for Inbox Zero. Adds functionality on top of Gmail like finding out which emails you need to reply to or need to follow up on.
* [lharries/whatsapp-mcp](https://github.com/lharries/whatsapp-mcp) ⭐ 5,009 | 🐛 80 | 🌐 Go | 📅 2025-07-13 🐍 🏎️ - An MCP server for searching your personal WhatsApp messages, contacts and sending messages to individuals or groups
* [korotovsky/slack-mcp-server](https://github.com/korotovsky/slack-mcp-server) ⭐ 843 | 🐛 16 | 🌐 Go | 📅 2025-10-18 📇 ☁️ - The most powerful MCP server for Slack Workspaces.
* [line/line-bot-mcp-server](https://github.com/line/line-bot-mcp-server) ⭐ 486 | 🐛 13 | 🌐 TypeScript | 📅 2025-10-24 🎖 📇 ☁️ - MCP Server for Integrating LINE Official Account
* [chigwell/telegram-mcp](https://github.com/chigwell/telegram-mcp) ⭐ 401 | 🐛 7 | 🌐 Python | 📅 2025-10-22 🐍 🏠 - Telegram API integration for accessing user data, managing dialogs (chats, channels, groups), retrieving messages, sending messages and handling read status.
* [joinly-ai/joinly](https://github.com/joinly-ai/joinly) ⭐ 381 | 🐛 3 | 🌐 Python | 📅 2025-10-05 🐍☁️ - MCP server to interact with browser-based meeting platforms (Zoom, Teams, Google Meet). Enables AI agents to send bots to online meetings, gather live transcripts, speak text, and send messages in the meeting chat.
* [InditexTech/mcp-teams-server](https://github.com/InditexTech/mcp-teams-server) ⭐ 326 | 🐛 8 | 🌐 Python | 📅 2025-10-20 🐍 ☁️ - MCP server that integrates Microsoft Teams messaging (read, post, mention, list members and threads)
* [softeria/ms-365-mcp-server](https://github.com/softeria/ms-365-mcp-server) ⭐ 310 | 🐛 4 | 🌐 TypeScript | 📅 2025-10-18 📇 ☁️ - MCP server that connects to Microsoft Office and the whole Microsoft 365 suite using Graph API (including Outlook, mail, files, Excel, calendar)
* [chaindead/telegram-mcp](https://github.com/chaindead/telegram-mcp) ⭐ 231 | 🐛 7 | 🌐 Go | 📅 2025-08-21 🏎️ 🏠 - Telegram API integration for accessing user data, managing dialogs (chats, channels, groups), retrieving messages, and handling read status
* [adhikasp/mcp-twikit](https://github.com/adhikasp/mcp-twikit) ⭐ 208 | 🐛 7 | 🌐 Python | 📅 2025-03-14 🐍 ☁️ - Interact with Twitter search and timeline
* [carterlasalle/mac\_messages\_mcp](https://github.com/carterlasalle/mac_messages_mcp) ⭐ 173 | 🐛 5 | 🌐 Python | 📅 2025-09-09 🏠 🍎 🚀 - An MCP server that securely interfaces with your iMessage database via the Model Context Protocol (MCP), allowing LLMs to query and analyze iMessage conversations. It includes robust phone number validation, attachment processing, contact management, group chat handling, and full support for sending and receiving messages.
* [saseq/discord-mcp](https://github.com/SaseQ/discord-mcp) ⭐ 102 | 🐛 1 | 🌐 Java | 📅 2025-08-11 ☕ 📇 🏠 💬 - A MCP server for the Discord integration. Enable your AI assistants to seamlessly interact with Discord. Enhance your Discord experience with powerful automation capabilities.
* [zcaceres/gtasks-mcp](https://github.com/zcaceres/gtasks-mcp) ⭐ 91 | 🐛 13 | 🌐 TypeScript | 📅 2025-02-02 📇 ☁️ - An MCP server to Manage Google Tasks
* [areweai/tsgram-mcp](https://github.com/areweai/tsgram-mcp) ⭐ 87 | 🐛 1 | 🌐 JavaScript | 📅 2025-06-26 - TSgram: Telegram + Claude with local workspace access on your phone in typescript. Read, write, and vibe code on the go!
* [hannesrudolph/imessage-query-fastmcp-mcp-server](https://github.com/hannesrudolph/imessage-query-fastmcp-mcp-server) ⭐ 70 | 🐛 3 | 🌐 Python | 📅 2025-05-27 🐍 🏠 🍎 - An MCP server that provides safe access to your iMessage database through Model Context Protocol (MCP), enabling LLMs to query and analyze iMessage conversations with proper phone number validation and attachment handling
* [ztxtxwd/open-feishu-mcp-server](https://github.com/ztxtxwd/open-feishu-mcp-server) ⭐ 62 | 🐛 7 | 🌐 TypeScript | 📅 2025-10-17 📇 ☁️ 🏠 - A Model Context Protocol (MCP) server with built-in Feishu OAuth authentication, supporting remote connections and providing comprehensive Feishu document management tools including block creation, content updates, and advanced features.
* [gitmotion/ntfy-me-mcp](https://github.com/gitmotion/ntfy-me-mcp) ⭐ 45 | 🐛 1 | 🌐 JavaScript | 📅 2025-08-06 📇 ☁️ 🏠 - An ntfy MCP server for sending/fetching ntfy notifications to your self-hosted ntfy server from AI Agents 📤 (supports secure token auth & more - use with npx or docker!)
* [sawa-zen/vrchat-mcp](https://github.com/sawa-zen/vrchat-mcp) ⭐ 44 | 🐛 1 | 🌐 TypeScript | 📅 2025-09-12 - 📇 🏠 This is an MCP server for interacting with the VRChat API. You can retrieve information about friends, worlds, avatars, and more in VRChat.
* [teddyzxcv/ntfy-mcp](https://github.com/teddyzxcv/ntfy-mcp) ⭐ 42 | 🐛 2 | 🌐 JavaScript | 📅 2025-03-25 - The MCP server that keeps you informed by sending the notification on phone using ntfy
* [Cactusinhand/mcp\_server\_notify](https://github.com/Cactusinhand/mcp_server_notify) ⭐ 36 | 🐛 1 | 🌐 Python | 📅 2025-08-18 🐍 🏠 - A MCP server that send desktop notifications with sound effect when agent tasks are completed.
* [AbdelStark/nostr-mcp](https://github.com/AbdelStark/nostr-mcp) ⭐ 35 | 🐛 4 | 🌐 TypeScript | 📅 2025-02-05 ☁️ - A Nostr MCP server that allows to interact with Nostr, enabling posting notes, and more.
* [agentmail-toolkit/mcp](https://github.com/agentmail-to/agentmail-toolkit/tree/main/mcp) ⭐ 30 | 🐛 2 | 🌐 Python | 📅 2025-08-11 🐍 💬 - An MCP server to create inboxes on the fly to send, receive, and take actions on email. We aren't AI agents for email, but email for AI Agents.
* [gotoolkits/wecombot](https://github.com/gotoolkits/mcp-wecombot-server.git) ⭐ 30 | 🐛 1 | 🌐 Go | 📅 2025-01-22 🚀 ☁️ - An MCP server application that sends various types of messages to the WeCom group robot.
* [jaipandya/producthunt-mcp-server](https://github.com/jaipandya/producthunt-mcp-server) ⭐ 30 | 🐛 4 | 🌐 Python | 📅 2025-04-19 🐍 🏠 - MCP server for Product Hunt. Interact with trending posts, comments, collections, users, and more.
* [i-am-bee/acp-mcp](https://github.com/i-am-bee/acp-mcp) ⚠️ Archived 🐍 💬 - An MCP server acting as an adapter into the [ACP](https://agentcommunicationprotocol.dev) ecosystem. Seamlessly exposes ACP agents to MCP clients, bridging the communication gap between the two protocols.
* [jagan-shanmugam/mattermost-mcp-host](https://github.com/jagan-shanmugam/mattermost-mcp-host) ⭐ 27 | 🐛 6 | 🌐 Python | 📅 2025-04-07 🐍 🏠 - A MCP server along with MCP host that provides access to Mattermost teams, channels and messages. MCP host is integrated as a bot in Mattermost with access to MCP servers that can be configured.
* [keturiosakys/bluesky-context-server](https://github.com/keturiosakys/bluesky-context-server) ⭐ 27 | 🐛 1 | 🌐 TypeScript | 📅 2025-08-10 📇 ☁️ - Bluesky instance integration for querying and interaction
* [arpitbatra123/mcp-googletasks](https://github.com/arpitbatra123/mcp-googletasks) ⭐ 23 | 🐛 0 | 🌐 TypeScript | 📅 2025-10-13 📇 ☁️ - An MCP server to interface with the Google Tasks API
* [Infobip/mcp](https://github.com/infobip/mcp) ⭐ 20 | 🐛 0 | 📅 2025-10-20 🎖️ ☁️ - Official Infobip MCP server for integrating Infobip global cloud communication platform. It equips AI agents with communication superpowers, allowing them to send and receive SMS and RCS messages, interact with WhatsApp and Viber, automate communication workflows, and manage customer data, all in a production-ready environment.
* [wyattjoh/imessage-mcp](https://github.com/wyattjoh/imessage-mcp) ⭐ 16 | 🐛 0 | 🌐 TypeScript | 📅 2025-08-05 📇 🏠 🍎 - A Model Context Protocol server for reading iMessage data from macOS.
* [Danielpeter-99/calcom-mcp](https://github.com/Danielpeter-99/calcom-mcp) ⭐ 12 | 🐛 1 | 🌐 Python | 📅 2025-06-02 🐍 🏠 - MCP server for Calcom. Manage event types, create bookings, and access Cal.com scheduling data through LLMs.
* [khan2a/telephony-mcp-server](https://github.com/khan2a/telephony-mcp-server) ⭐ 10 | 🐛 0 | 🌐 Python | 📅 2025-07-22 🐍 💬 - MCP Telephony server for automating voice calls with Speech-to-Text and Speech Recognition to summarize call conversations. Send and receive SMS, detect voicemail, and integrate with Vonage APIs for advanced telephony workflows.
* [gerkensm/callcenter.js-mcp](https://github.com/gerkensm/callcenter.js-mcp) ⭐ 9 | 🐛 3 | 🌐 TypeScript | 📅 2025-10-20 📇 ☁️ - An MCP server to make phone calls using VoIP/SIP and OpenAI's Realtime API and observe the transcript.
* [OverQuotaAI/chatterboxio-mcp-server](https://github.com/OverQuotaAI/chatterboxio-mcp-server) ⭐ 8 | 🐛 1 | 🌐 TypeScript | 📅 2025-07-15 📇 ☁️ - MCP server implementation for ChatterBox.io, enabling AI agents to send bots to online meetings (Zoom, Google Meet) and obtain transcripts and recordings.
* [YCloud-Developers/ycloud-whatsapp-mcp-server](https://github.com/YCloud-Developers/ycloud-whatsapp-mcp-server) ⭐ 7 | 🐛 2 | 🌐 TypeScript | 📅 2025-04-07 📇 🏠 - MCP server for WhatsApp Business Platform by YCloud.
* [PhononX/cv-mcp-server](https://github.com/PhononX/cv-mcp-server) ⭐ 3 | 🐛 0 | 🌐 TypeScript | 📅 2025-10-10 🎖️ 📇 🏠 ☁️ 🍎 🪟 🐧 - MCP Server that connects AI Agents to [Carbon Voice](https://getcarbon.app). Create, manage, and interact with voice messages, conversations, direct messages, folders, voice memos, AI actions and more in [Carbon Voice](https://getcarbon.app).
* [userad/didlogic\_mcp](https://github.com/UserAd/didlogic_mcp) ⭐ 1 | 🐛 2 | 🌐 Python | 📅 2025-10-09 🐍 ☁️ - An MCP server for [DIDLogic](https://didlogic.com). Adds functionality to manage SIP endpoints, numbers and destinations.

### 👤 <a name="customer-data-platforms"></a>Customer Data Platforms

Provides access to customer profiles inside of customer data platforms

* [antv/mcp-server-chart](https://github.com/antvis/mcp-server-chart) ⭐ 3,043 | 🐛 26 | 🌐 TypeScript | 📅 2025-10-17 🎖️ 📇 ☁️ - A Model Context Protocol server for generating visual charts using [AntV](https://github.com/antvis).
* [hustcc/mcp-mermaid](https://github.com/hustcc/mcp-mermaid) ⭐ 260 | 🐛 3 | 🌐 TypeScript | 📅 2025-10-14 📇 🏠 - Generate [mermaid](https://mermaid.js.org/) diagram and chart with AI MCP dynamically.
* [OpenDataMCP/OpenDataMCP](https://github.com/OpenDataMCP/OpenDataMCP) ⭐ 139 | 🐛 6 | 🌐 Python | 📅 2024-12-20 🐍 ☁️ - Connect any Open Data to any LLM with Model Context Protocol.
* [hustcc/mcp-echarts](https://github.com/hustcc/mcp-echarts) ⭐ 137 | 🐛 6 | 🌐 TypeScript | 📅 2025-10-20 📇 🏠 - Generate visual charts using [Apache ECharts](https://echarts.apache.org) with AI MCP dynamically.
* [tinybirdco/mcp-tinybird](https://github.com/tinybirdco/mcp-tinybird) ⚠️ Archived 🐍 ☁️ - An MCP server to interact with a Tinybird Workspace from any MCP client.
* [sergehuber/inoyu-mcp-unomi-server](https://github.com/sergehuber/inoyu-mcp-unomi-server) ⭐ 6 | 🐛 5 | 🌐 JavaScript | 📅 2025-09-12 📇 ☁️ - An MCP server to access and updates profiles on an Apache Unomi CDP server.
* [iaptic/mcp-server-iaptic](https://github.com/iaptic/mcp-server-iaptic) ⭐ 4 | 🐛 3 | 🌐 TypeScript | 📅 2025-03-02 🎖️ 📇 ☁️ - Connect with [iaptic](https://www.iaptic.com) to ask about your Customer Purchases, Transaction data and App Revenue statistics.

### 🗄️ <a name="databases"></a>Databases

Secure database access with schema inspection capabilities. Enables querying and analyzing data with configurable security controls including read-only access.

* [modelcontextprotocol/server-postgres](https://github.com/modelcontextprotocol/servers/tree/main/src/postgres) ⭐ 71,117 | 🐛 277 | 🌐 TypeScript | 📅 2025-10-24 📇 🏠 - PostgreSQL database integration with schema inspection and query capabilities
* [modelcontextprotocol/server-sqlite](https://github.com/modelcontextprotocol/servers/tree/main/src/sqlite) ⭐ 71,117 | 🐛 277 | 🌐 TypeScript | 📅 2025-10-24 🐍 🏠 - SQLite database operations with built-in analysis features
* [googleapis/genai-toolbox](https://github.com/googleapis/genai-toolbox) ⭐ 11,060 | 🐛 198 | 🌐 Go | 📅 2025-10-23 🏎️ ☁️ - Open source MCP server specializing in easy, fast, and secure tools for Databases.
* [get-convex/convex-backend](https://stack.convex.dev/convex-mcp-server) 📇 ☁️ - Convex database integration to introspect tables, functions, and run oneoff queries ([Source](https://github.com/get-convex/convex-backend/blob/main/npm-packages/convex/src/cli/mcp.ts) ⭐ 7,785 | 🐛 84 | 🌐 Rust | 📅 2025-10-24)
* [bram2w/baserow](https://github.com/bram2w/baserow) ⭐ 3,018 | 🐛 1,286 | 🌐 Python | 📅 2025-10-23 - Baserow database integration with table search, list, and row create, read, update, and delete capabilities.
* [supabase-community/supabase-mcp](https://github.com/supabase-community/supabase-mcp) ⭐ 2,205 | 🐛 64 | 🌐 TypeScript | 📅 2025-10-23 🎖️ 📇 ☁️ - Official Supabase MCP server to connect AI assistants directly with your Supabase project and allows them to perform tasks like managing tables, fetching config, and querying data.
* [crystaldba/postgres-mcp](https://github.com/crystaldba/postgres-mcp) ⭐ 1,375 | 🐛 34 | 🌐 Python | 📅 2025-05-16 🐍 🏠 - All-in-one MCP server for Postgres development and operations, with tools for performance analysis, tuning, and health checks
* [qdrant/mcp-server-qdrant](https://github.com/qdrant/mcp-server-qdrant) ⭐ 1,025 | 🐛 31 | 🌐 Python | 📅 2025-08-19 🐍 🏠 - A Qdrant MCP server
* [designcomputer/mysql\_mcp\_server](https://github.com/designcomputer/mysql_mcp_server) ⭐ 939 | 🐛 51 | 🌐 Python | 📅 2025-06-05 🐍 🏠 - MySQL database integration with configurable access controls, schema inspection, and comprehensive security guidelines
* [benborla29/mcp-server-mysql](https://github.com/benborla/mcp-server-mysql) ⭐ 874 | 🐛 26 | 🌐 JavaScript | 📅 2025-09-08 ☁️ 🏠 - MySQL database integration in NodeJS with configurable access controls and schema inspection
* [alexanderzuev/supabase-mcp-server](https://github.com/alexander-zuev/supabase-mcp-server) ⭐ 804 | 🐛 6 | 🌐 Python | 📅 2025-09-26 - Supabase MCP Server with support for SQL query execution and database exploration tools
* [neo4j-contrib/mcp-neo4j](https://github.com/neo4j-contrib/mcp-neo4j) ⭐ 760 | 🐛 24 | 🌐 Python | 📅 2025-10-11 🐍 🏠 - Model Context Protocol with Neo4j (Run queries, Knowledge Graph Memory, Manaage Neo4j Aura Instances)
* [ClickHouse/mcp-clickhouse](https://github.com/ClickHouse/mcp-clickhouse) ⭐ 567 | 🐛 24 | 🌐 Python | 📅 2025-10-23 🐍 ☁️ - ClickHouse database integration with schema inspection and query capabilities
* [neondatabase/mcp-server-neon](https://github.com/neondatabase/mcp-server-neon) ⭐ 494 | 🐛 17 | 🌐 TypeScript | 📅 2025-10-23 📇 ☁️ — An MCP Server for creating and managing Postgres databases using Neon Serverless Postgres
* [centralmind/gateway](https://github.com/centralmind/gateway) ⭐ 490 | 🐛 15 | 🌐 Go | 📅 2025-07-18 🏎️ 🏠 🍎 🪟 - MCP and MCP SSE Server that automatically generate API based on database schema and data. Supports PostgreSQL, Clickhouse, MySQL, Snowflake, BigQuery, Supabase
* [subnetmarco/pgmcp](https://github.com/subnetmarco/pgmcp) ⭐ 486 | 🐛 1 | 🌐 Go | 📅 2025-09-25 🏎️ 🏠 - Natural language PostgreSQL queries with automatic streaming, read-only safety, and universal database compatibility.
* [Canner/wren-engine](https://github.com/Canner/wren-engine) ⭐ 476 | 🐛 47 | 🌐 Java | 📅 2025-10-22 🐍 🦀 🏠 - The Semantic Engine for Model Context Protocol(MCP) Clients and AI Agents
* [xing5/mcp-google-sheets](https://github.com/xing5/mcp-google-sheets) ⭐ 464 | 🐛 11 | 🌐 Python | 📅 2025-08-26 🐍 ☁️ - A Model Context Protocol server for interacting with Google Sheets. This server provides tools to create, read, update, and manage spreadsheets through the Google Sheets API.
* [chroma-core/chroma-mcp](https://github.com/chroma-core/chroma-mcp) ⭐ 397 | 🐛 13 | 🌐 Python | 📅 2025-09-17 🎖️ 🐍 ☁️ 🏠 - Chroma MCP server to access local and cloud Chroma instances for retrieval capabilities
* [runekaagaard/mcp-alchemy](https://github.com/runekaagaard/mcp-alchemy) ⭐ 347 | 🐛 0 | 🌐 Python | 📅 2025-08-15 🐍 🏠 - Universal SQLAlchemy-based database integration supporting PostgreSQL, MySQL, MariaDB, SQLite, Oracle, MS SQL Server and many more databases. Features schema and relationship inspection, and large dataset analysis capabilities.
* [domdomegg/airtable-mcp-server](https://github.com/domdomegg/airtable-mcp-server) ⭐ 323 | 🐛 9 | 🌐 TypeScript | 📅 2025-10-20 📇 🏠 - Airtable database integration with schema inspection, read and write capabilities
* [FreePeak/db-mcp-server](https://github.com/FreePeak/db-mcp-server) ⭐ 298 | 🐛 11 | 🌐 Go | 📅 2025-09-13 🏎️ 🏠 – A high-performance multi-database MCP server built with Golang, supporting MySQL & PostgreSQL (NoSQL coming soon). Includes built-in tools for query execution, transaction management, schema exploration, query building, and performance analysis, with seamless Cursor integration for enhanced database workflows.
* [redis/mcp-redis](https://github.com/redis/mcp-redis) ⭐ 297 | 🐛 11 | 🌐 Python | 📅 2025-10-23 🐍 🏠 - The Redis official MCP Server offers an interface to manage and search data in Redis.
* [wenb1n-dev/mysql\_mcp\_server\_pro](https://github.com/wenb1n-dev/mysql_mcp_server_pro) ⭐ 268 | 🐛 11 | 🌐 Python | 📅 2025-08-28  🐍 🏠 - Supports SSE, STDIO; not only limited to MySQL's CRUD functionality; also includes database exception analysis capabilities; controls database permissions based on roles; and makes it easy for developers to extend tools with customization
* [kiliczsh/mcp-mongo-server](https://github.com/kiliczsh/mcp-mongo-server) ⭐ 263 | 🐛 2 | 🌐 TypeScript | 📅 2025-05-27 📇 🏠 - A Model Context Protocol Server for MongoDB
* [pab1it0/prometheus-mcp-server](https://github.com/pab1it0/prometheus-mcp-server) ⭐ 255 | 🐛 2 | 🌐 Python | 📅 2025-10-22 🐍 ☁️ -  Query and analyze Prometheus, open-source monitoring system.
* [gannonh/firebase-mcp](https://github.com/gannonh/firebase-mcp) ⭐ 218 | 🐛 12 | 🌐 TypeScript | 📅 2025-10-20 🔥 ⛅️ - Firebase services including Auth, Firestore and Storage.
* [XGenerationLab/xiyan\_mcp\_server](https://github.com/XGenerationLab/xiyan_mcp_server) ⭐ 216 | 🐛 9 | 🌐 Python | 📅 2025-09-26 📇 ☁️ — An MCP server that supports fetching data from a database using natural language queries, powered by XiyanSQL as the text-to-SQL LLM.
* [cr7258/elasticsearch-mcp-server](https://github.com/cr7258/elasticsearch-mcp-server) ⭐ 215 | 🐛 6 | 🌐 Python | 📅 2025-10-19 🐍 🏠 - MCP Server implementation that provides Elasticsearch interaction
* [zilliztech/mcp-server-milvus](https://github.com/zilliztech/mcp-server-milvus) ⭐ 190 | 🐛 15 | 🌐 Python | 📅 2025-10-22 🐍 🏠 ☁️ - MCP Server for Milvus / Zilliz, making it possible to interact with your database.
* [furey/mongodb-lens](https://github.com/furey/mongodb-lens) ⭐ 188 | 🐛 4 | 🌐 JavaScript | 📅 2025-04-23 📇 🏠 - MongoDB Lens: Full Featured MCP Server for MongoDB Databases
* [quarkiverse/mcp-server-jdbc](https://github.com/quarkiverse/quarkus-mcp-servers/tree/main/jdbc) ⭐ 172 | 🐛 24 | 🌐 Java | 📅 2025-07-28 ☕ 🏠 - Connect to any JDBC-compatible database and query, insert, update, delete, and more.
* [QuantGeekDev/mongo-mcp](https://github.com/QuantGeekDev/mongo-mcp) ⭐ 169 | 🐛 14 | 🌐 TypeScript | 📅 2025-03-15 📇 🏠 - MongoDB integration that enables LLMs to interact directly with databases.
* [isaacwasserman/mcp-snowflake-server](https://github.com/isaacwasserman/mcp-snowflake-server) ⭐ 167 | 🐛 9 | 🌐 Python | 📅 2025-10-07 🐍 ☁️ - Snowflake integration implementing read and (optional) write operations as well as insight tracking
* [ktanaka101/mcp-server-duckdb](https://github.com/ktanaka101/mcp-server-duckdb) ⭐ 167 | 🐛 3 | 🌐 Python | 📅 2025-05-05 🐍 🏠 - DuckDB database integration with schema inspection and query capabilities
* [Snowflake-Labs/mcp](https://github.com/Snowflake-Labs/mcp) ⭐ 164 | 🐛 8 | 🌐 Python | 📅 2025-10-23 🐍 ☁️ - Open-source MCP server for Snowflake from official Snowflake-Labs supports prompting Cortex Agents, querying structured & unstructured data, object management, SQL execution, semantic view querying, and more. RBAC, fine-grained CRUD controls, and all authentication methods supported.
* [weaviate/mcp-server-weaviate](https://github.com/weaviate/mcp-server-weaviate) ⭐ 154 | 🐛 4 | 🌐 Go | 📅 2025-05-22 🐍 📇 ☁️ - An MCP Server to connect to your Weaviate collections as a knowledge base as well as using Weaviate as a chat memory store.
* [aliyun/alibabacloud-tablestore-mcp-server](https://github.com/aliyun/alibabacloud-tablestore-mcp-server) ⭐ 148 | 🐛 2 | 🌐 Java | 📅 2025-10-17 ☕ 🐍 ☁️ - MCP service for Tablestore, features include adding documents, semantic search for documents based on vectors and scalars, RAG-friendly, and serverless.
* [sirmews/mcp-pinecone](https://github.com/sirmews/mcp-pinecone) ⭐ 146 | 🐛 6 | 🌐 Python | 📅 2025-01-31 🐍 ☁️ - Pinecone integration with vector search capabilities
* [ergut/mcp-bigquery-server](https://github.com/ergut/mcp-bigquery-server) ⭐ 128 | 🐛 7 | 🌐 JavaScript | 📅 2025-05-24 📇 ☁️ - Server implementation for Google BigQuery integration that enables direct BigQuery database access and querying capabilities
* [f4ww4z/mcp-mysql-server](https://github.com/f4ww4z/mcp-mysql-server) ⭐ 122 | 🐛 11 | 🌐 JavaScript | 📅 2025-05-03 📇 🏠 - Node.js-based MySQL database integration that provides secure MySQL database operations
* [LucasHild/mcp-server-bigquery](https://github.com/LucasHild/mcp-server-bigquery) ⭐ 120 | 🐛 4 | 🌐 Python | 📅 2025-05-30 🐍 ☁️ - BigQuery database integration with schema inspection and query capabilities
* [confluentinc/mcp-confluent](https://github.com/confluentinc/mcp-confluent) ⭐ 112 | 🐛 9 | 🌐 TypeScript | 📅 2025-10-23 🐍 ☁️ - Confluent integration to interact with Confluent Kafka and Confluent Cloud REST APIs.
* [hannesrudolph/sqlite-explorer-fastmcp-mcp-server](https://github.com/hannesrudolph/sqlite-explorer-fastmcp-mcp-server) ⭐ 88 | 🐛 5 | 🌐 Python | 📅 2025-07-18 🐍 🏠 - An MCP server that provides safe, read-only access to SQLite databases through Model Context Protocol (MCP). This server is built with the FastMCP framework, which enables LLMs to explore and query SQLite databases with built-in safety features and query validation.
* [tuannvm/mcp-trino](https://github.com/tuannvm/mcp-trino) ⭐ 76 | 🐛 11 | 🌐 Go | 📅 2025-10-22 🏎️ ☁️ - A Go implementation of a Model Context Protocol (MCP) server for Trino
* [TheRaLabs/legion-mcp](https://github.com/TheRaLabs/legion-mcp) ⭐ 72 | 🐛 7 | 🌐 Python | 📅 2025-05-11 🐍 🏠 Universal database MCP server supporting multiple database types including PostgreSQL, Redshift, CockroachDB, MySQL, RDS MySQL, Microsoft SQL Server, BigQuery, Oracle DB, and SQLite.
* [ChristianHinge/dicom-mcp](https://github.com/ChristianHinge/dicom-mcp) ⭐ 68 | 🐛 7 | 🌐 Python | 📅 2025-05-05 🐍 ☁️ 🏠 - DICOM integration to query, read, and move medical images and reports from PACS and other DICOM compliant systems.
* [jparkerweb/mcp-sqlite](https://github.com/jparkerweb/mcp-sqlite) ⭐ 58 | 🐛 1 | 🌐 JavaScript | 📅 2025-06-02 📇 🏠 - Model Context Protocol (MCP) server that provides comprehensive SQLite database interaction capabilities.
* [edwinbernadus/nocodb-mcp-server](https://github.com/edwinbernadus/nocodb-mcp-server) ⭐ 51 | 🐛 0 | 🌐 JavaScript | 📅 2025-08-22 📇 ☁️ - Nocodb database integration, read and write capabilities
* [pab1it0/adx-mcp-server](https://github.com/pab1it0/adx-mcp-server) ⭐ 49 | 🐛 0 | 🌐 Python | 📅 2025-08-23 🐍 ☁️ - Query and analyze Azure Data Explorer databases
* [joshuarileydev/supabase-mcp-server](https://github.com/joshuarileydev/supabase) ⭐ 48 | 🐛 4 | 🌐 JavaScript | 📅 2024-12-06 - Supabase MCP Server for managing and creating projects and organisations in Supabase
* [Zhwt/go-mcp-mysql](https://github.com/Zhwt/go-mcp-mysql) ⭐ 45 | 🐛 1 | 🌐 Go | 📅 2025-08-19 🏎️ 🏠 – Easy to use, zero dependency MySQL MCP server built with Golang with configurable readonly mode and schema inspection.
* [memgraph/mcp-memgraph](https://github.com/memgraph/ai-toolkit/tree/main/integrations/mcp-memgraph) ⭐ 41 | 🐛 18 | 🌐 Python | 📅 2025-10-23 🐍 🏠 - Memgraph MCP Server - includes a tool to run a query against Memgraph and a schema resource.
* [rashidazarang/airtable-mcp](https://github.com/rashidazarang/airtable-mcp) ⭐ 41 | 🐛 1 | 🌐 JavaScript | 📅 2025-09-25 🐍 ☁️ - Connect AI tools directly to Airtable. Query, create, update, and delete records using natural language. Features include base management, table operations, schema manipulation, record filtering, and data migration through a standardized MCP interface.
* [freema/mcp-gsheets](https://github.com/freema/mcp-gsheets) ⭐ 32 | 🐛 5 | 🌐 TypeScript | 📅 2025-10-20 📇 ☁️ - MCP server for Google Sheets API integration with comprehensive reading, writing, formatting, and sheet management capabilities.
* [prisma/mcp](https://github.com/prisma/mcp) ⭐ 30 | 🐛 0 | 🌐 JavaScript | 📅 2025-10-07 📇 ☁️ 🏠 - Gives LLMs the ability to manage Prisma Postgres databases (e.g. spin up new databases and run migrations or queries).
* [idoru/influxdb-mcp-server](https://github.com/idoru/influxdb-mcp-server) ⭐ 27 | 🐛 8 | 🌐 JavaScript | 📅 2025-05-23 📇 ☁️ 🏠 - Run queries against InfluxDB OSS API v2.
* [fireproof-storage/mcp-database-server](https://github.com/fireproof-storage/mcp-database-server) ⭐ 26 | 🐛 4 | 🌐 JavaScript | 📅 2024-12-19 📇 ☁️ - Fireproof ledger database with multi-user sync
* [VictoriaMetrics-Community/mcp-victorialogs](https://github.com/VictoriaMetrics-Community/mcp-victorialogs) ⭐ 25 | 🐛 0 | 🌐 Go | 📅 2025-10-20 🎖️ 🏎️ 🏠 - Provides comprehensive integration with your [VictoriaLogs instance APIs](https://docs.victoriametrics.com/victorialogs/querying/#http-api) and [documentation](https://docs.victoriametrics.com/victorialogs/) for working with logs, investigating and debugging tasks related to your VictoriaLogs instances.
* [GreptimeTeam/greptimedb-mcp-server](https://github.com/GreptimeTeam/greptimedb-mcp-server) ⭐ 23 | 🐛 4 | 🌐 Python | 📅 2025-06-09 🐍 🏠 - MCP Server for querying GreptimeDB.
* [ydb/ydb-mcp](https://github.com/ydb-platform/ydb-mcp) ⭐ 23 | 🐛 4 | 🌐 Python | 📅 2025-08-29 🎖️ 🐍 ☁️ - MCP server for interacting with [YDB](https://ydb.tech) databases
* [c4pt0r/mcp-server-tidb](https://github.com/c4pt0r/mcp-server-tidb) ⭐ 22 | 🐛 3 | 🌐 Python | 📅 2025-04-15 🐍 ☁️ - TiDB database integration with schema inspection and query capabilities
* [Couchbase-Ecosystem/mcp-server-couchbase](https://github.com/Couchbase-Ecosystem/mcp-server-couchbase) ⭐ 22 | 🐛 3 | 🌐 Python | 📅 2025-10-22 🎖️ 🐍 ☁️ 🏠 - Couchbase MCP server provides unfied access to both Capella cloud and self-managed clusters for document operations, SQL++ queries and natural language data analysis.
* [InfluxData/influxdb3\_mcp\_server](https://github.com/influxdata/influxdb3_mcp_server) ⭐ 19 | 🐛 4 | 🌐 TypeScript | 📅 2025-09-13 🎖️ 📇 🏠 ☁️ - Official MCP server for InfluxDB 3 Core/Enterprise/Cloud Dedicated
* [Dataring-engineering/mcp-server-trino](https://github.com/Dataring-engineering/mcp-server-trino) ⭐ 18 | 🐛 4 | 🌐 Python | 📅 2025-04-22 🐍 ☁️ - Trino MCP Server to query and access data from Trino Clusters.
* [niledatabase/nile-mcp-server](https://github.com/niledatabase/nile-mcp-server) ⭐ 16 | 🐛 4 | 🌐 TypeScript | 📅 2025-03-10 MCP server for Nile's Postgres platform - Manage and query Postgres databases, tenants, users, auth using LLMs
* [openlink/mcp-server-sqlalchemy](https://github.com/OpenLinkSoftware/mcp-sqlalchemy-server) ⭐ 16 | 🐛 1 | 🌐 Python | 📅 2025-05-23 🐍 🏠 - An MCP server for generic Database Management System (DBMS) Connectivity via SQLAlchemy using Python ODBC (pyodbc)
* [xexr/mcp-libsql](https://github.com/Xexr/mcp-libsql) ⭐ 14 | 🐛 1 | 🌐 TypeScript | 📅 2025-06-03 📇 🏠 ☁️ - Production-ready MCP server for libSQL databases with comprehensive security and management tools.
* [davewind/mysql-mcp-server](https://github.com/dave-wind/mysql-mcp-server) ⭐ 11 | 🐛 2 | 🌐 JavaScript | 📅 2025-04-27 🏎️ 🏠 A – user-friendly read-only mysql mcp server for cursor and n8n...
* [Aiven-Open/mcp-aiven](https://github.com/Aiven-Open/mcp-aiven) ⭐ 10 | 🐛 4 | 🌐 Python | 📅 2025-05-14 - 🐍 ☁️ 🎖️ -  Navigate your [Aiven projects](https://go.aiven.io/mcp-server) and interact with the PostgreSQL®, Apache Kafka®, ClickHouse® and OpenSearch® services
* [henilcalagiya/google-sheets-mcp](https://github.com/henilcalagiya/google-sheets-mcp) ⭐ 10 | 🐛 0 | 🌐 Python | 📅 2025-09-11 🐍 🏠 - Your AI Assistant's Gateway to Google Sheets! 25 powerful tools for seamless Google Sheets automation via MCP.
* [jovezhong/mcp-timeplus](https://github.com/jovezhong/mcp-timeplus) ⭐ 10 | 🐛 1 | 🌐 Python | 📅 2025-07-24 🐍 ☁️ - MCP server for Apache Kafka and Timeplus. Able to list Kafka topics, poll Kafka messages, save Kafka data locally and query streaming data with SQL via Timeplus
* [openlink/mcp-server-odbc](https://github.com/OpenLinkSoftware/mcp-odbc-server) ⭐ 9 | 🐛 2 | 🌐 TypeScript | 📅 2025-07-23 🐍 🏠 - An MCP server for generic Database Management System (DBMS) Connectivity via the Open Database Connectivity (ODBC) protocol
* [openlink/mcp-server-jdbc](https://github.com/OpenLinkSoftware/mcp-jdbc-server) ⭐ 8 | 🐛 1 | 🌐 Java | 📅 2025-07-22 🐍 🏠 - An MCP server for generic Database Management System (DBMS) Connectivity via the Java Database Connectivity (JDBC) protocol
* [schemacrawler/SchemaCrawler-MCP-Server-Usage](https://github.com/schemacrawler/SchemaCrawler-MCP-Server-Usage) ⭐ 8 | 🐛 0 | 📅 2025-10-03 🎖️ ☕ – Connect to any relational database, and be able to get valid SQL, and ask questions like what does a certain column prefix mean.
* [iunera/druid-mcp-server](https://github.com/iunera/druid-mcp-server) ⭐ 7 | 🐛 0 | 🌐 Java | 📅 2025-10-16 ☕ ☁️ 🏠 - Comprehensive MCP server for Apache Druid that provides extensive tools, resources, and prompts for managing and analyzing Druid clusters.
* [yincongcyincong/VictoriaMetrics-mcp-server](https://github.com/yincongcyincong/VictoriaMetrics-mcp-server) ⭐ 7 | 🐛 2 | 🌐 JavaScript | 📅 2025-05-16 🐍 🏠 - An MCP server for interacting with VictoriaMetrics database.
* [yannbrrd/simple\_snowflake\_mcp](https://github.com/YannBrrd/simple_snowflake_mcp) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2025-09-24 🐍 ☁️ - Simple Snowflake MCP server that works behind a corporate proxy. Read and write (optional) operations
* [amineelkouhen/mcp-cockroachdb](https://github.com/amineelkouhen/mcp-cockroachdb) ⭐ 5 | 🐛 1 | 🌐 Python | 📅 2025-07-25 🐍 ☁️ - A Model Context Protocol server for managing, monitoring, and querying data in [CockroachDB](https://cockroachlabs.com).
* [ferrants/memvid-mcp-server](https://github.com/ferrants/memvid-mcp-server) ⭐ 5 | 🐛 1 | 🌐 Python | 📅 2025-06-20 🐍 🏠 - Python Streamable HTTP Server you can run locally to interact with [memvid](https://github.com/Olow304/memvid) ⭐ 10,165 | 🐛 49 | 🌐 Python | 📅 2025-10-12 storage and semantic search.
* [hydrolix/mcp-hydrolix](https://github.com/hydrolix/mcp-hydrolix) ⭐ 5 | 🐛 2 | 🌐 Python | 📅 2025-10-23 🎖️ 🐍 ☁️ - Hydrolix time-series datalake integration providing schema exploration and query capabilities to LLM-based workflows.
* [tradercjz/dolphindb-mcp-server](https://github.com/tradercjz/dolphindb-mcp-server) ⭐ 4 | 🐛 1 | 🌐 Python | 📅 2025-07-31 🐍 ☁️ - TDolphinDB database integration with schema inspection and query capabilities
* [KashiwaByte/vikingdb-mcp-server](https://github.com/KashiwaByte/vikingdb-mcp-server) ⭐ 3 | 🐛 4 | 🌐 Python | 📅 2025-08-18 🐍 ☁️ - VikingDB integration with collection and index introduction, vector store and search capabilities.
* [skysqlinc/skysql-mcp](https://github.com/skysqlinc/skysql-mcp) ⭐ 2 | 🐛 1 | 🌐 Python | 📅 2025-08-20 🎖️ ☁️ - Serverless MariaDB Cloud DB MCP server. Tools to launch, delete, execute SQL and work with DB level AI agents for accurate text-2-sql and conversations.
* [s2-streamstore/s2-sdk-typescript](https://github.com/s2-streamstore/s2-sdk-typescript) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2025-10-24 🎖️ 📇 ☁️ - Official MCP server for the S2.dev serverless stream platform.

### 📊 <a name="data-platforms"></a>Data Platforms

Data Platforms for data integration, transformation and pipeline orchestration.

* [dbt-labs/dbt-mcp](https://github.com/dbt-labs/dbt-mcp) ⭐ 402 | 🐛 24 | 🌐 Python | 📅 2025-10-22 🎖️ 🐍 🏠 ☁️ - Official MCP server for [dbt (data build tool)](https://www.getdbt.com/product/what-is-dbt) providing integration with dbt Core/Cloud CLI, project metadata discovery, model information, and semantic layer querying capabilities.
* [keboola/keboola-mcp-server](https://github.com/keboola/keboola-mcp-server) ⭐ 80 | 🐛 3 | 🌐 Python | 📅 2025-10-23 🐍 - interact with Keboola Connection Data Platform. This server provides tools for listing and accessing data from Keboola Storage API.
* [JordiNei/mcp-databricks-server](https://github.com/JordiNeil/mcp-databricks-server) ⭐ 41 | 🐛 9 | 🌐 Python | 📅 2025-04-24 🐍 ☁️ - Connect to Databricks API, allowing LLMs to run SQL queries, list jobs, and get job status.
* [aywengo/kafka-schema-reg-mcp](https://github.com/aywengo/kafka-schema-reg-mcp) ⭐ 23 | 🐛 2 | 🌐 Python | 📅 2025-10-23 🐍 ☁️ 🏠 🍎 🪟 🐧 - Comprehensive Kafka Schema Registry MCP server with 48 tools for multi-registry management, schema migration, and enterprise features.
* [mattijsdp/dbt-docs-mcp](https://github.com/mattijsdp/dbt-docs-mcp) ⭐ 19 | 🐛 2 | 🌐 Python | 📅 2025-08-19 🐍 🏠 - MCP server for dbt-core (OSS) users as the official dbt MCP only supports dbt Cloud. Supports project metadata, model and column-level lineage and dbt documentation.
* [yashshingvi/databricks-genie-MCP](https://github.com/yashshingvi/databricks-genie-MCP) ⭐ 10 | 🐛 1 | 🌐 Python | 📅 2025-04-18 🐍 ☁️ - A server that connects to the Databricks Genie API, allowing LLMs to ask natural language questions, run SQL queries, and interact with Databricks conversational agents.
* [flowcore/mcp-flowcore-platform](https://github.com/flowcore-io/mcp-flowcore-platform) ⭐ 7 | 🐛 3 | 🌐 TypeScript | 📅 2025-05-12 🎖️ 📇 ☁️ 🏠 - Interact with Flowcore to perform actions, ingest data, and analyse, cross reference and utilise any data in your data cores, or in public data cores; all with human language.
* [jwaxman19/qlik-mcp](https://github.com/jwaxman19/qlik-mcp) ⭐ 5 | 🐛 0 | 🌐 TypeScript | 📅 2025-07-27 📇 ☁️ - MCP Server for Qlik Cloud API that enables querying applications, sheets, and extracting data from visualizations with comprehensive authentication and rate limiting support.

### 💻 <a name="developer-tools"></a>Developer Tools

Tools and integrations that enhance the development workflow and environment management.

* [GLips/Figma-Context-MCP](https://github.com/GLips/Figma-Context-MCP) ⭐ 11,368 | 🐛 32 | 🌐 TypeScript | 📅 2025-10-14 📇 🏠 - Provide coding agents direct access to Figma data to help them one-shot design implementation.
* [idosal/git-mcp](https://github.com/idosal/git-mcp) ⭐ 6,746 | 🐛 48 | 🌐 TypeScript | 📅 2025-08-22 📇 ☁️ - [gitmcp.io](https://gitmcp.io/) is a generic remote MCP server to connect to ANY [GitHub](https://www.github.com) repository or project for documentation
* [21st-dev/Magic-MCP](https://github.com/21st-dev/magic-mcp) ⭐ 3,839 | 🐛 17 | 🌐 TypeScript | 📅 2025-06-09 - Create crafted UI components inspired by the best 21st.dev design engineers.
* [haris-musa/excel-mcp-server](https://github.com/haris-musa/excel-mcp-server) ⭐ 2,671 | 🐛 34 | 🌐 Python | 📅 2025-08-11 🐍 🏠 - An Excel manipulation server providing workbook creation, data operations, formatting, and advanced features (charts, pivot tables, formulae).
* [Jpisnice/shadcn-ui-mcp-server](https://github.com/Jpisnice/shadcn-ui-mcp-server) ⭐ 2,395 | 🐛 6 | 🌐 TypeScript | 📅 2025-10-23 📇 🏠 - MCP server that gives AI assistants seamless access to shadcn/ui v4 components, blocks, demos, and metadata.
* [mobile-next/mobile-mcp](https://github.com/mobile-next/mobile-mcp) ⭐ 2,296 | 🐛 35 | 🌐 TypeScript | 📅 2025-10-20 📇 🏠 🐧 🍎 - MCP Server for Android/iOS application and device automation, development and app scraping. Simulator/Emulator/Physical devices like iPhone, Google Pixel, Samsung supported.
* [cjo4m06/mcp-shrimp-task-manager](https://github.com/cjo4m06/mcp-shrimp-task-manager) ⭐ 1,818 | 🐛 30 | 🌐 JavaScript | 📅 2025-08-21 📇 ☁️ 🏠 – A programming-focused task management system that boosts coding agents like Cursor AI with advanced task memory, self-reflection, and dependency management. [ShrimpTaskManager](https://cjo4m06.github.io/mcp-shrimp-task-manager)
* [isaacphi/mcp-language-server](https://github.com/isaacphi/mcp-language-server) ⭐ 1,219 | 🐛 37 | 🌐 Go | 📅 2025-10-01 🏎️ 🏠 - MCP Language Server helps MCP enabled clients navigate codebases more easily by giving them access to semantic tools like get definition, references, rename, and diagnostics.
* [ios-simulator-mcp](https://github.com/joshuayoes/ios-simulator-mcp) ⭐ 1,169 | 🐛 11 | 🌐 JavaScript | 📅 2025-10-07 📇 🏠 🍎 - A Model Context Protocol (MCP) server for interacting with iOS simulators. This server allows you to interact with iOS simulators by getting information about them, controlling UI interactions, and inspecting UI elements.
* [jetbrains/mcpProxy](https://github.com/JetBrains/mcpProxy) ⭐ 926 | 🐛 36 | 🌐 JavaScript | 📅 2025-08-18 🎖️ 📇 🏠 - Connect to JetBrains IDE
* [snaggle-ai/openapi-mcp-server](https://github.com/snaggle-ai/openapi-mcp-server) ⭐ 835 | 🐛 8 | 🌐 JavaScript | 📅 2025-10-23 🏎️ 🏠 - Connect any HTTP/REST API server using an Open API spec (v3)
* [lpigeon/ros-mcp-server](https://github.com/lpigeon/ros-mcp-server) ⭐ 767 | 🐛 14 | 🌐 Python | 📅 2025-10-23 🐍 🏠 🍎 🪟 🐧 - The ROS MCP Server supports robot control by converting user-issued natural language commands into ROS or ROS2 control commands.
* [ckreiling/mcp-server-docker](https://github.com/ckreiling/mcp-server-docker) ⭐ 638 | 🐛 10 | 🌐 Python | 📅 2025-06-05 🐍 🏠 - Integrate with Docker to manage containers, images, volumes, and networks.
* [zcaceres/fetch-mcp](https://github.com/zcaceres/fetch-mcp) ⭐ 625 | 🐛 7 | 🌐 TypeScript | 📅 2025-09-02 📇 🏠 - An MCP server to flexibly fetch JSON, text, and HTML data
* [automation-ai-labs/mcp-link](https://github.com/automation-ai-labs/mcp-link) ⭐ 563 | 🐛 8 | 🌐 Go | 📅 2025-04-03 🏎️ 🏠 - Seamlessly Integrate Any API with AI Agents (with OpenAPI Schema)
* [bgauryy/octocode-mcp](https://github.com/bgauryy/octocode-mcp) ⭐ 511 | 🐛 3 | 🌐 TypeScript | 📅 2025-10-17 ☁️ 📇 🍎 🪟 🐧 - AI-powered developer assistant that enables advanced research, analysis and discovery across GitHub and NPM realms in realtime.
* [etsd-tech/mcp-pointer](https://github.com/etsd-tech/mcp-pointer) ⭐ 483 | 🐛 2 | 🌐 TypeScript | 📅 2025-10-01 📇 🏠 🍎 🪟 🐧 - Visual DOM element selector for agentic coding tools. Chrome extension + MCP server bridge for Claude Code, Cursor, Windsurf etc. Option+Click to capture elements.
* [jasonjmcghee/claude-debugs-for-you](https://github.com/jasonjmcghee/claude-debugs-for-you) ⭐ 447 | 🐛 12 | 🌐 TypeScript | 📅 2025-08-12 📇 🏠 - An MCP Server and VS Code Extension which enables (language agnostic) automatic debugging via breakpoints and expression evaluation.
* [vivekvells/mcp-pandoc](https://github.com/vivekVells/mcp-pandoc) ⭐ 438 | 🐛 4 | 🌐 Python | 📅 2025-09-16 🗄️ 🚀 - MCP server for seamless document format conversion using Pandoc, supporting Markdown, HTML, PDF, DOCX (.docx), csv and more.
* [QuantGeekDev/docker-mcp](https://github.com/QuantGeekDev/docker-mcp) ⭐ 410 | 🐛 8 | 🌐 Python | 📅 2024-12-14 🏎️ 🏠 - Docker container management and operations through MCP
* [r-huijts/xcode-mcp-server](https://github.com/r-huijts/xcode-mcp-server) ⭐ 326 | 🐛 0 | 🌐 TypeScript | 📅 2025-08-26 📇 🏠 🍎 - Xcode integration for project management, file operations, and build automation
* [TencentEdgeOne/edgeone-pages-mcp](https://github.com/TencentEdgeOne/edgeone-pages-mcp) ⭐ 313 | 🐛 8 | 🌐 TypeScript | 📅 2025-10-17 📇 ☁️ - An MCP service for deploying HTML content to EdgeOne Pages and obtaining a publicly accessible URL.
* [utensils/mcp-nixos](https://github.com/utensils/mcp-nixos) ⭐ 313 | 🐛 9 | 🌐 HTML | 📅 2025-10-18 🐍 🏠 - MCP server providing accurate information about NixOS packages, system options, Home Manager configurations, and nix-darwin macOS settings to prevent AI hallucinations.
* [gitkraken/gk-cli](https://github.com/gitkraken/gk-cli) ⭐ 308 | 🐛 8 | 📅 2025-10-21 🎖️ 🏎️ 🏠 ☁️ 🍎 🪟 🐧 - A CLI for interacting with GitKraken APIs. Includes an MCP server via `gk mcp` that not only wraps GitKraken APIs, but also Jira, GitHub, GitLab, and more. Works with local tools and remote services.
* [OpenZeppelin/contracts-wizard](https://github.com/OpenZeppelin/contracts-wizard/tree/master/packages/mcp) ⭐ 285 | 🐛 30 | 🌐 TypeScript | 📅 2025-10-23 - A Model Context Protocol (MCP) server that allows AI agents to generate secure smart contracts in multiples languages based on [OpenZeppelin Wizard templates](https://wizard.openzeppelin.com/).
* [SDGLBL/mcp-claude-code](https://github.com/SDGLBL/mcp-claude-code) ⭐ 273 | 🐛 6 | 🌐 Python | 📅 2025-08-29 🐍 🏠 - An implementation of Claude Code capabilities using MCP, enabling AI code understanding, modification, and project analysis with comprehensive tool support.
* [InditexTech/mcp-server-simulator-ios-idb](https://github.com/InditexTech/mcp-server-simulator-ios-idb) ⭐ 269 | 🐛 5 | 🌐 TypeScript | 📅 2025-09-02 📇 🏠 🍎 - A Model Context Protocol (MCP) server that enables LLMs to interact with iOS simulators (iPhone, iPad, etc.) through natural language commands.
* [hyperb1iss/droidmind](https://github.com/hyperb1iss/droidmind) ⭐ 252 | 🐛 7 | 🌐 Python | 📅 2025-05-16 🐍 🏠 - Control Android devices with AI through MCP, enabling device control, debugging, system analysis, and UI automation with a comprehensive security framework.
* [admica/FileScopeMCP](https://github.com/admica/FileScopeMCP) ⭐ 249 | 🐛 8 | 🌐 HTML | 📅 2025-09-04 🐍 📇 🦀 - Analyzes your codebase identifying important files based on dependency relationships. Generates diagrams and importance scores, helping AI assistants understand the codebase.
* [YuChenSSR/mindmap-mcp-server](https://github.com/YuChenSSR/mindmap-mcp-server) ⭐ 203 | 🐛 5 | 🌐 Python | 📅 2025-05-20 🐍 🏠 - A Model Context Protocol (MCP) server for generating a beautiful interactive mindmap.
* [Govcraft/rust-docs-mcp-server](https://github.com/Govcraft/rust-docs-mcp-server) ⭐ 202 | 🐛 14 | 🌐 Rust | 📅 2025-06-23 🦀 🏠 - Provides up-to-date documentation context for a specific Rust crate to LLMs via an MCP tool, using semantic search (embeddings) and LLM summarization.
* [VSCode Devtools](https://github.com/biegehydra/BifrostMCP) ⭐ 179 | 🐛 8 | 🌐 TypeScript | 📅 2025-07-15 📇 - Connect to VSCode ide and use semantic tools like `find_usages`
* [Comet-ML/Opik-MCP](https://github.com/comet-ml/opik-mcp) ⭐ 176 | 🐛 29 | 🌐 TypeScript | 📅 2025-09-16 🎖️ 📇 ☁️ 🏠 - Use natural language to explore LLM observability, traces, and monitoring data captured by Opik.
* [tumf/mcp-text-editor](https://github.com/tumf/mcp-text-editor) ⭐ 165 | 🐛 2 | 🌐 Python | 📅 2025-09-07 🐍 🏠 - A line-oriented text file editor. Optimized for LLM tools with efficient partial file access to minimize token usage.
* [pskill9/website-downloader](https://github.com/pskill9/website-downloader) ⭐ 144 | 🐛 3 | 🌐 JavaScript | 📅 2024-12-24 🗄️ 🚀 - This MCP server provides a tool to download entire websites using wget. It preserves the website structure and converts links to work locally.
* [langfuse/mcp-server-langfuse](https://github.com/langfuse/mcp-server-langfuse) ⭐ 143 | 🐛 9 | 🌐 TypeScript | 📅 2025-02-16 🐍 🏠 - MCP server to access and manage LLM application prompts created with [Langfuse](origin/\[https:/langfuse.com/]\(https:/langfuse.com/docs/prompts/get-started\)) Prompt Management.
* [delano/postman-mcp-server](https://github.com/delano/postman-mcp-server) ⭐ 141 | 🐛 8 | 🌐 TypeScript | 📅 2025-09-13 📇 ☁️ - Interact with [Postman API](https://www.postman.com/postman/postman-public-workspace/)
* [joshuarileydev/app-store-connect-mcp-server](https://github.com/JoshuaRileyDev/app-store-connect-mcp-server) ⭐ 135 | 🐛 4 | 🌐 TypeScript | 📅 2025-09-02 📇 🏠 - An MCP server to communicate with the App Store Connect API for iOS Developers
* [posthog/mcp](https://github.com/posthog/mcp) ⭐ 135 | 🐛 18 | 🌐 TypeScript | 📅 2025-10-10 🎖️ 📇 ☁️ - An MCP server for interacting with PostHog analytics, feature flags, error tracking and more.
* [sammcj/mcp-package-version](https://github.com/sammcj/mcp-package-version) ⭐ 118 | 🐛 4 | 🌐 Go | 📅 2025-05-14 📇 🏠 - An MCP Server to help LLMs suggest the latest stable package versions when writing code.
* [yangkyeongmo@/mcp-server-apache-airflow](https://github.com/yangkyeongmo/mcp-server-apache-airflow) ⭐ 104 | 🐛 7 | 🌐 Python | 📅 2025-10-17 🐍 🏠 - MCP server that connects to [Apache Airflow](https://airflow.apache.org/) using official client.
* [janreges/ai-distiller-mcp](https://github.com/janreges/ai-distiller) ⭐ 99 | 🐛 5 | 🌐 C | 📅 2025-08-03 🏎️ 🏠 - Extracts essential code structure from large codebases into AI-digestible format, helping AI agents write code that correctly uses existing APIs on the first attempt.
* [sapientpants/sonarqube-mcp-server](https://github.com/sapientpants/sonarqube-mcp-server) ⭐ 98 | 🐛 4 | 🌐 TypeScript | 📅 2025-10-21 🦀 ☁️ 🏠 - A Model Context Protocol (MCP) server that integrates with SonarQube to provide AI assistants with access to code quality metrics, issues, and quality gate statuses
* [storybookjs/addon-mcp](https://github.com/storybookjs/addon-mcp) ⭐ 89 | 🐛 6 | 🌐 TypeScript | 📅 2025-10-23 📇 🏠 - Help agents automatically write and test stories for your UI components.
* [aashari/mcp-server-atlassian-bitbucket](https://github.com/aashari/mcp-server-atlassian-bitbucket) ⭐ 83 | 🐛 22 | 🌐 TypeScript | 📅 2025-10-20 📇 ☁️ - Atlassian Bitbucket Cloud integration. Enables AI systems to interact with repositories, pull requests, workspaces, and code in real time.
* [st3v3nmw/sourcerer-mcp](https://github.com/st3v3nmw/sourcerer-mcp) ⭐ 81 | 🐛 1 | 🌐 Go | 📅 2025-09-05 🏎️ ☁️ - MCP for semantic code search & navigation that reduces token waste
* [docker/hub-mcp](https://github.com/docker/hub-mcp) ⭐ 78 | 🐛 0 | 🌐 TypeScript | 📅 2025-10-10 🎖️ 📇 ☁️ 🏠 - Official MCP server to interact with Docker Hub, providing access to repositories, hub search and Docker Hardened Images
* [xcodebuild](https://github.com/ShenghaiWang/xcodebuild) ⭐ 76 | 🐛 0 | 🌐 Python | 📅 2025-08-15 🍎 Build iOS Xcode workspace/project and feed back errors to llm.
* [lamemind/mcp-server-multiverse](https://github.com/lamemind/mcp-server-multiverse) ⭐ 74 | 🐛 6 | 🌐 TypeScript | 📅 2025-06-04 📇 🏠 🛠️ - A middleware server that enables multiple isolated instances of the same MCP servers to coexist independently with unique namespaces and configurations.
* [xzq.xu/jvm-mcp-server](https://github.com/xzq-xu/jvm-mcp-server) ⭐ 70 | 🐛 2 | 🌐 Python | 📅 2025-09-01 📇 🏠  - An implementation project of a JVM-based MCP (Model Context Protocol) server.
* [augmnt/augments-mcp-server](https://github.com/augmnt/augments-mcp-server) ⭐ 69 | 🐛 2 | 🌐 Python | 📅 2025-09-20 📇 ☁️ 🏠 - Transform Claude Code with intelligent, real-time access to 90+ framework documentation sources. Get accurate, up-to-date code generation that follows current best practices for React, Next.js, Laravel, FastAPI, Tailwind CSS, and more.
* [ReAPI-com/mcp-openapi](https://github.com/ReAPI-com/mcp-openapi) ⭐ 69 | 🐛 7 | 🌐 TypeScript | 📅 2025-03-30 📇 🏠 - MCP server that lets LLMs know everything about your OpenAPI specifications to discover, explain and generate code/mock data
* [CircleCI/mcp-server-circleci](https://github.com/CircleCI-Public/mcp-server-circleci) ⭐ 67 | 🐛 16 | 🌐 TypeScript | 📅 2025-10-01 📇 ☁️ Enable AI Agents to fix build failures from CircleCI.
* [YuChenSSR/multi-ai-advisor](https://github.com/YuChenSSR/multi-ai-advisor-mcp) ⭐ 66 | 🐛 2 | 🌐 TypeScript | 📅 2025-04-02 📇 🏠 - A Model Context Protocol (MCP) server that queries multiple Ollama models and combines their responses, providing diverse AI perspectives on a single question.
* [stass/lldb-mcp](https://github.com/stass/lldb-mcp) ⭐ 64 | 🐛 2 | 🌐 Python | 📅 2025-03-26 🐍 🏠 🐧 🍎 - A MCP server for LLDB enabling AI binary and core file analysis, debugging, disassembling.
* [zillow/auto-mobile](https://github.com/zillow/auto-mobile) ⭐ 61 | 🐛 14 | 🌐 TypeScript | 📅 2025-10-21 📇 🏠 🐧  - Tool suite built around an MCP server for Android automation for developer workflow and testing
* [ckanthony/gin-mcp](https://github.com/ckanthony/gin-mcp) ⭐ 58 | 🐛 3 | 🌐 Go | 📅 2025-08-17 🏎️ ☁️ 📟 🪟 🐧 🍎 - A zero-configuration Go library to automatically expose existing Gin web framework APIs as MCP tools.
* [WiseVision/mcp\_server\_ros\_2](https://github.com/wise-vision/mcp_server_ros_2) ⭐ 56 | 🐛 4 | 🌐 Python | 📅 2025-10-23 🐍 🤖 - MCP server for ROS2 enabling AI-driven robotics applications and services.
* [kadykov/mcp-openapi-schema-explorer](https://github.com/kadykov/mcp-openapi-schema-explorer) ⭐ 54 | 🐛 4 | 🌐 TypeScript | 📅 2025-10-20 📇 ☁️ 🏠 - Token-efficient access to OpenAPI/Swagger specs via MCP Resources.
* [abrinsmead/mindpilot-mcp](https://github.com/abrinsmead/mindpilot-mcp) ⭐ 53 | 🐛 10 | 🌐 TypeScript | 📅 2025-08-13 📇 🏠 - Visualizes code, architecture and other concepts as mermaid diagrams in a locally hosted web app. Just ask your agent to "show me this in a diagram".
* [lpigeon/unitree-go2-mcp-server](https://github.com/lpigeon/unitree-go2-mcp-server) ⭐ 52 | 🐛 1 | 🌐 Python | 📅 2025-05-12 🐍 🏠 🐧 - The Unitree Go2 MCP Server is a server built on the MCP that enables users to control the Unitree Go2 robot using natural language commands interpreted by a LLM.
* [azer/react-analyzer-mcp](https://github.com/azer/react-analyzer-mcp) ⭐ 49 | 🐛 0 | 🌐 TypeScript | 📅 2025-04-09 📇 🏠 - Analyze React code locally, generate docs / llm.txt for whole project at once
* [mrexodia/user-feedback-mcp](https://github.com/mrexodia/user-feedback-mcp) ⭐ 48 | 🐛 1 | 🌐 Python | 📅 2025-03-26 🐍 🏠 - Simple MCP Server to enable a human-in-the-loop workflow in tools like Cline and Cursor.
* [qainsights/jmeter-mcp-server](https://github.com/QAInsights/jmeter-mcp-server) ⭐ 47 | 🐛 5 | 🌐 Python | 📅 2025-06-15 🐍 🏠 - JMeter MCP Server for performance testing
* [joshuarileydev/simulator-mcp-server](https://github.com/JoshuaRileyDev/simulator-mcp-server) ⭐ 46 | 🐛 6 | 🌐 JavaScript | 📅 2024-12-13 📇 🏠 - An MCP server to control iOS Simulators
* [hloiseaufcms/mcp-gopls](https://github.com/hloiseaufcms/mcp-gopls) ⭐ 45 | 🐛 1 | 🌐 Go | 📅 2025-04-09 🏎️ 🏠 - A MCP server for interacting with [Go's Language Server Protocol (gopls)](https://github.com/golang/tools/tree/master/gopls) ⭐ 7,809 | 🐛 105 | 🌐 Go | 📅 2025-10-24 and benefit from advanced Go code analysis features.
* [yWorks/mcp-typescribe](https://github.com/yWorks/mcp-typescribe) ⭐ 43 | 🐛 0 | 🌐 TypeScript | 📅 2025-10-17 📇 🏠 - MCP server that provides Typescript API information efficiently to the agent to enable it to work with untrained APIs
* [buildkite/buildkite-mcp-server](https://github.com/buildkite/buildkite-mcp-server) ⭐ 39 | 🐛 9 | 🌐 Go | 📅 2025-10-20 🎖️ 🏎️ 🏠 ☁️ 🍎 🪟 🐧 - Official MCP server for Buildkite. Create new pipelines, diagnose and fix failures, trigger builds, monitor job queues, and more.
* [IvanAmador/vercel-ai-docs-mcp](https://github.com/IvanAmador/vercel-ai-docs-mcp) ⭐ 38 | 🐛 3 | 🌐 TypeScript | 📅 2025-04-04 📇 🏠 - A Model Context Protocol (MCP) server that provides AI-powered search and querying capabilities for the Vercel AI SDK documentation.
* [aashari/mcp-server-atlassian-confluence](https://github.com/aashari/mcp-server-atlassian-confluence) ⭐ 36 | 🐛 15 | 🌐 TypeScript | 📅 2025-10-20 📇 ☁️ - Atlassian Confluence Cloud integration. Enables AI systems to interact with Confluence spaces, pages, and content with automatic ADF to Markdown conversion.
* [IlyaGulya/gradle-mcp-server](https://github.com/IlyaGulya/gradle-mcp-server) ⭐ 36 | 🐛 3 | 🌐 Kotlin | 📅 2025-07-15 🏠 - Gradle integration using the Gradle Tooling API to inspect projects, execute tasks, and run tests with per-test result reporting
* [aashari/mcp-server-atlassian-jira](https://github.com/aashari/mcp-server-atlassian-jira) ⭐ 33 | 🐛 20 | 🌐 TypeScript | 📅 2025-10-20 📇 ☁️ - Atlassian Jira Cloud integration. Enables AI systems to interact with Jira projects, issues, comments, and related development information in real time.
* [jsdelivr/globalping-mcp-server](https://github.com/jsdelivr/globalping-mcp-server) ⭐ 33 | 🐛 7 | 🌐 TypeScript | 📅 2025-10-18 🎖️ 📇 ☁️ - The Globalping MCP server provides users and LLMs access to run network tools like ping, traceroute, mtr, HTTP and DNS resolve from thousands of locations around the world.
* [Rootly-AI-Labs/Rootly-MCP-server](https://github.com/Rootly-AI-Labs/Rootly-MCP-server) ⭐ 32 | 🐛 1 | 🌐 Python | 📅 2025-10-23 🎖️ 🐍 ☁️ 🍎 - MCP server for the incident management platform [Rootly](https://rootly.com/).
* [zaizaizhao/mcp-swagger-server](https://github.com/zaizaizhao/mcp-swagger-server) ⭐ 32 | 🐛 2 | 🌐 TypeScript | 📅 2025-10-10 📇 ☁️ 🏠 - A Model Context Protocol (MCP) server that converts OpenAPI/Swagger specifications to MCP format, enabling AI assistants to interact with REST APIs through standardized protocol.
* [hungthai1401/bruno-mcp](https://github.com/hungthai1401/bruno-mcp) ⭐ 31 | 🐛 0 | 🌐 JavaScript | 📅 2025-08-16 📇 🏠 - A MCP server for interacting with [Bruno API Client](https://www.usebruno.com/).
* [yikakia/godoc-mcp-server](https://github.com/yikakia/godoc-mcp-server) ⭐ 31 | 🐛 0 | 🌐 Go | 📅 2025-07-15 🏎️ ☁️ 🪟 🐧 🍎 - Query Go package information on pkg.go.dev
* [CodeLogicIncEngineering/codelogic-mcp-server](https://github.com/CodeLogicIncEngineering/codelogic-mcp-server) ⭐ 30 | 🐛 5 | 🌐 Python | 📅 2025-10-13 🎖️ 🐍 ☁️ 🍎 🪟 🐧 - Official MCP server for CodeLogic, providing access to code dependency analytics, architectural risk analysis, and impact assessment tools.
* [freema/mcp-design-system-extractor](https://github.com/freema/mcp-design-system-extractor) ⭐ 30 | 🐛 1 | 🌐 TypeScript | 📅 2025-08-28 📇 🏠 - Extracts component information from Storybook design systems. Provides HTML, styles, props, dependencies, theme tokens and component metadata for AI-powered design system analysis.
* [zenml-io/mcp-zenml](https://github.com/zenml-io/mcp-zenml) ⭐ 30 | 🐛 1 | 🌐 Python | 📅 2025-10-21 🐍 🏠 ☁️ - An MCP server to connect with your [ZenML](https://www.zenml.io) MLOps and LLMOps pipelines
* [api7/apisix-mcp](https://github.com/api7/apisix-mcp) ⭐ 29 | 🐛 2 | 🌐 TypeScript | 📅 2025-06-16 🎖️ 📇 🏠 MCP Server that support for querying and managing all resource in [Apache APISIX](https://github.com/apache/apisix) ⭐ 15,753 | 🐛 323 | 🌐 Lua | 📅 2025-10-23.
* [promptexecution/just-mcp](https://github.com/promptexecution/just-mcp) ⭐ 29 | 🐛 2 | 🌐 Rust | 📅 2025-07-26 🦀 🏠 - Justfile integration that enables LLMs to execute any CLI or script commands with parameters safely and easily, with environment variable support and comprehensive testing.
* [hijaz/postmancer](https://github.com/hijaz/postmancer) ⭐ 28 | 🐛 1 | 🌐 TypeScript | 📅 2025-08-19 📇 🏠 - A MCP server for replacing Rest Clients like Postman/Insomnia, by allowing your LLM to maintain and use api collections.
* [InhiblabCore/mcp-image-compression](https://github.com/InhiblabCore/mcp-image-compression) ⭐ 28 | 🐛 2 | 🌐 TypeScript | 📅 2025-06-14 🐍 🏠 - MCP server for local compression of various image formats.
* [artmann/package-registry-mcp](https://github.com/artmann/package-registry-mcp) ⭐ 25 | 🐛 1 | 🌐 TypeScript | 📅 2025-08-06 🏠 📇 🍎 🪟 🐧 - MCP server for searching and getting up-to-date information about NPM, Cargo, PyPi, and NuGet packages.
* [endorhq/cli](https://github.com/endorhq/cli) ⭐ 25 | 🐛 1 | 📅 2025-07-01 📇 ☁️ 🏠 🪟 🐧 🍎 - Endor lets your AI agents run services like MariaDB, Postgres, Redis, Memcached, Alpine, or Valkey in isolated sandboxes. Get pre-configured applications that boot in less than 5 seconds.
* [j4c0bs/mcp-server-sql-analyzer](https://github.com/j4c0bs/mcp-server-sql-analyzer) ⭐ 25 | 🐛 0 | 🌐 Python | 📅 2025-07-01 🐍 - MCP server that provides SQL analysis, linting, and dialect conversion using [SQLGlot](https://github.com/tobymao/sqlglot) ⭐ 8,475 | 🐛 6 | 🌐 Python | 📅 2025-10-23
* [Yutarop/ros-mcp](https://github.com/Yutarop/ros-mcp) ⭐ 25 | 🐛 1 | 🌐 Python | 📅 2025-08-19 🐍 🏠 🐧 - MCP server that supports ROS2 topics, services, and actions communication, and controls robots using natural language.
* [Tommertom/awesome-ionic-mcp](https://github.com/Tommertom/awesome-ionic-mcp) ⭐ 23 | 🐛 2 | 🌐 TypeScript | 📅 2025-06-12 📇 🏠 - Your Ionic coding buddy enabled via MCP – build awesome mobile apps using React/Angular/Vue or even Vanilla JS!
* [XixianLiang/HarmonyOS-mcp-server](https://github.com/XixianLiang/HarmonyOS-mcp-server) ⭐ 23 | 🐛 2 | 🌐 Python | 📅 2025-08-18 🐍 🏠 - Control HarmonyOS-next devices with AI through MCP. Support device control and UI automation.
* [higress-group/higress-ops-mcp-server](https://github.com/higress-group/higress-ops-mcp-server) ⭐ 22 | 🐛 6 | 🌐 Python | 📅 2025-03-29 🐍 🏠 - MCP server that provides comprehensive tools for managing [Higress](https://github.com/alibaba/higress) ⭐ 6,664 | 🐛 647 | 🌐 Go | 📅 2025-10-23 gateway configurations and operations.
* [Jktfe/serveMyAPI](https://github.com/Jktfe/serveMyAPI) ⭐ 22 | 🐛 3 | 🌐 TypeScript | 📅 2025-04-23 📇 🏠 🍎 - A personal MCP (Model Context Protocol) server for securely storing and accessing API keys across projects using the macOS Keychain.
* [OctoMind-dev/octomind-mcp](https://github.com/OctoMind-dev/octomind-mcp) ⭐ 21 | 🐛 4 | 🌐 TypeScript | 📅 2025-10-23 📇 ☁️ - lets your preferred AI agent create & run fully managed [Octomind](https://www.octomind.dev/) end-to-end tests from your codebase or other data sources like Jira, Slack or TestRail.
* [cqfn/aibolit-mcp-server](https://github.com/cqfn/aibolit-mcp-server) ⭐ 18 | 🐛 5 | 🌐 TypeScript | 📅 2025-05-16 ☕ - Helping Your AI Agent Identify Hotspots for Refactoring; Help AI Understand How to 'Make Code Better'
* [reflagcom/mcp](https://github.com/reflagcom/javascript/tree/main/packages/cli#model-context-protocol) ⭐ 18 | 🐛 11 | 🌐 TypeScript | 📅 2025-10-22 🎖️ 📇 ☁️ - Flag features directly from chat in your IDE with [Reflag](https://reflag.com).
* [tgeselle/bugsnag-mcp](https://github.com/tgeselle/bugsnag-mcp) ⭐ 18 | 🐛 2 | 🌐 API Blueprint | 📅 2025-04-13 📇 ☁️ - An MCP server for interacting with [Bugsnag](https://www.bugsnag.com/)
* [ryan0204/github-repo-mcp](https://github.com/Ryan0204/github-repo-mcp) ⭐ 17 | 🐛 1 | 🌐 JavaScript | 📅 2025-04-25 📇 ☁️ 🪟 🐧 🍎 - GitHub Repo MCP allow your AI assistants browse GitHub repositories, explore directories, and view file contents.
* [qainsights/k6-mcp-server](https://github.com/QAInsights/k6-mcp-server) ⭐ 16 | 🐛 6 | 🌐 Python | 📅 2025-04-06 🐍 🏠 - Grafana k6 MCP Server for performance testing
* [linw1995/nvim-mcp](https://github.com/linw1995/nvim-mcp) ⭐ 15 | 🐛 4 | 🌐 Rust | 📅 2025-10-21 🦀 🏠 🍎 🪟 🐧  -  A MCP server to interact with Neovim
* [axliupore/mcp-code-runner](https://github.com/axliupore/mcp-code-runner) ⭐ 14 | 🐛 1 | 🌐 TypeScript | 📅 2025-04-11 📇 🏠 - An MCP server for running code locally via Docker and supporting multiple programming languages.
* [gofireflyio/firefly-mcp](https://github.com/gofireflyio/firefly-mcp) ⭐ 14 | 🐛 5 | 🌐 TypeScript | 📅 2025-09-25 🎖️ 📇 ☁️ - Integrates, discovers, manages, and codifies cloud resources with [Firefly](https://firefly.ai).
* [Hypersequent/qasphere-mcp](https://github.com/Hypersequent/qasphere-mcp) ⭐ 14 | 🐛 5 | 🌐 JavaScript | 📅 2025-10-21 🎖️ 📇 ☁️ - Integration with [QA Sphere](https://qasphere.com/) test management system, enabling LLMs to discover, summarize, and interact with test cases directly from AI-powered IDEs
* [ukkit/memcord](https://github.com/ukkit/memcord) ⭐ 14 | 🐛 2 | 🌐 Python | 📅 2025-10-06 🐍 🏠 🐧 🍎 - A MCP server that keeps your chat history organized and searchable—with AI-powered summaries, secure memory, and full control.
* [Pratyay/mac-monitor-mcp](https://github.com/Pratyay/mac-monitor-mcp) ⭐ 14 | 🐛 1 | 🌐 Python | 📅 2025-10-15 🐍 🏠 🍎 - Identifies resource-intensive processes on macOS and provides performance improvement suggestions.
* [sequa-ai/sequa-mcp](https://github.com/sequa-ai/sequa-mcp) ⭐ 14 | 🐛 1 | 🌐 TypeScript | 📅 2025-10-07 📇 ☁️ 🐧 🍎 🪟 - Stop stitching context for Copilot and Cursor. With Sequa MCP, your AI tools know your entire codebase and docs out of the box.
* [vasayxtx/mcp-prompt-engine](https://github.com/vasayxtx/mcp-prompt-engine) ⭐ 13 | 🐛 1 | 🌐 Go | 📅 2025-10-01 🏎️ 🏠 🪟️ 🐧 🍎 - MCP server for managing and serving dynamic prompt templates using elegant and powerful text template engine.
* [ambar/simctl-mcp](https://github.com/ambar/simctl-mcp) ⭐ 12 | 🐛 0 | 🌐 TypeScript | 📅 2025-08-22 📇 🏠 🍎 A MCP server implementation for iOS Simulator control.
* [currents-dev/currents-mcp](https://github.com/currents-dev/currents-mcp) ⭐ 12 | 🐛 0 | 🌐 TypeScript | 📅 2025-10-15 🎖️ 📇 ☁️ Enable AI Agents to fix Playwright test failures reported to [Currents](https://currents.dev).
* [ArchAI-Labs/fastmcp-sonarqube-metrics](https://github.com/ArchAI-Labs/fastmcp-sonarqube-metrics) ⭐ 11 | 🐛 1 | 🌐 Python | 📅 2025-09-01 🐍 🏠 🪟 🐧 🍎 -  A Model Context Protocol (MCP) server that provides a set of tools for retrieving information about SonarQube projects like metrics (actual and historical), issues, health status.
* [ConfigCat/mcp-server](https://github.com/configcat/mcp-server) ⭐ 11 | 🐛 2 | 🌐 TypeScript | 📅 2025-10-21 🎖️ 📇 ☁️ - MCP server for interacting with ConfigCat feature flag platform. Supports managing feature flags, configs, environments, products and organizations.
* [jordandalton/restcsv-mcp-server](https://github.com/JordanDalton/RestCsvMcpServer) ⭐ 10 | 🐛 3 | 🌐 TypeScript | 📅 2025-04-17 📇 ☁️ - An MCP server for CSV files.
* [yiwenlu66/PiloTY](https://github.com/yiwenlu66/PiloTY) ⭐ 10 | 🐛 0 | 🌐 Python | 📅 2025-06-30 🐍 🏠 - AI pilot for PTY operations enabling agents to control interactive terminals with stateful sessions, SSH connections, and background process management
* [qainsights/locust-mcp-server](https://github.com/QAInsights/locust-mcp-server) ⭐ 9 | 🐛 3 | 🌐 Python | 📅 2025-04-06 🐍 🏠 - Locust MCP Server for performance testing
* [tipdotmd/tip-md-x402-mcp-server](https://github.com/tipdotmd/tip-md-x402-mcp-server) ⭐ 9 | 🐛 1 | 🌐 TypeScript | 📅 2025-09-11 📇 ☁️ - MCP server for cryptocurrency tipping through AI interfaces using x402 payment protocol and CDP Wallet.
* [Chunkydotdev/bldbl-mcp](https://github.com/chunkydotdev/bldbl-mcp) ⭐ 8 | 🐛 1 | 🌐 TypeScript | 📅 2025-07-03 📇 ☁️ 🍎 🪟 🐧 - Official MCP server for Buildable AI-powered development platform [bldbl.dev](https://bldbl.dev). Enables AI assistants to manage tasks, track progress, get project context, and collaborate with humans on software projects.
* [gorosun/unified-diff-mcp](https://github.com/gorosun/unified-diff-mcp) ⭐ 8 | 🐛 1 | 🌐 TypeScript | 📅 2025-06-02 📇 🏠 - Generate and visualize unified diff comparisons with beautiful HTML/PNG output, supporting side-by-side and line-by-line views for filesystem dry-run integration
* [PromptExecution/cratedocs-mcp](https://github.com/promptexecution/cratedocs-mcp) ⭐ 8 | 🐛 0 | 🌐 Rust | 📅 2025-07-06 🦀 🏠 - Outputs short-form Rust crate derived traits,interfaces, etc. from AST (uses same api as rust-analyzer), output limits (token estimation) & crate docs w/regex stripping.
* [opslevel/opslevel-mcp](https://github.com/opslevel/opslevel-mcp) ⭐ 8 | 🐛 12 | 🌐 Go | 📅 2025-10-13 🎖️ 🏎️ ☁️ 🪟 🍎 🐧 - Official MCP Server for [OpsLevel](https://www.opslevel.com)
* [picahq/mcp](https://github.com/picahq/mcp) ⭐ 8 | 🐛 0 | 🌐 TypeScript | 📅 2025-10-22 🎖️ 🦀 📇 ☁️ - One MCP for all your integrations — powered by [Pica](https://www.picaos.com), the infrastructure for intelligent, collaborative agents.
* [narumiruna/gitingest-mcp](https://github.com/narumiruna/gitingest-mcp) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2025-10-17 🐍 🏠 - A MCP server that uses [gitingest](https://github.com/cyclotruc/gitingest) ⭐ 12,906 | 🐛 25 | 🌐 Python | 📅 2025-10-23 to convert any Git repository into a simple text digest of its codebase.
* [alimo7amed93/webhook-tester-mcp](https://github.com/alimo7amed93/webhook-tester-mcp) ⭐ 6 | 🐛 3 | 🌐 Python | 📅 2025-04-25  🐍 ☁️ – A FastMCP-based server for interacting with webhook-test.com. Enables users to create, retrieve, and delete webhooks locally using Claude.
* [akramIOT/MCP\_AI\_SOC\_Sher](https://github.com/akramIOT/MCP_AI_SOC_Sher) ⭐ 5 | 🐛 1 | 🌐 Python | 📅 2025-04-30  🐍 ☁️ 📇 - MCP Server to do dynamic AI SOC Security Threat analysis for a  Text2SQL  AI Agent.
* [mumez/pharo-smalltalk-interop-mcp-server](https://github.com/mumez/pharo-smalltalk-interop-mcp-server) ⭐ 5 | 🐛 0 | 🌐 Python | 📅 2025-10-21 🐍 🏠 - Pharo Smalltalk integration enabling code evaluation, class/method introspection, package management, test execution, and project installation for interactive development with Pharo images.
* [spacecode-ai/SpaceBridge-MCP](https://github.com/spacecode-ai/SpaceBridge-MCP) ⚠️ Archived 🐍 🏠 🍎 🐧 - Bring structure and preserve context in vibe coding by automatically tracking issues.
* [Webvizio/mcp](https://github.com/Webvizio/mcp) ⭐ 4 | 🐛 0 | 🌐 TypeScript | 📅 2025-09-19 🎖️ 📇 - Automatically converts feedback and bug reports from websites and web apps into actionable, context-enriched developer tasks. Delivered straight to your AI coding tools, the Webvizio MCP Server ensures your AI agent has all the data it needs to solve tasks with speed and accuracy.
* [HainanZhao/mcp-gitlab-jira](https://github.com/HainanZhao/mcp-gitlab-jira) ⭐ 3 | 🐛 2 | 🌐 TypeScript | 📅 2025-09-05 📇 ☁️ 🏠 - Unified MCP server for GitLab and Jira: manage projects, merge requests, files, releases and tickets with AI agents.
* [InsForge/insforge-mcp](https://github.com/InsForge/insforge-mcp) ⭐ 3 | 🐛 3 | 🌐 TypeScript | 📅 2025-10-20 📇 ☁️ - AI-native backend-as-a-service platform enabling AI agents to build and manage full-stack applications. Provides Auth, Database (PostgreSQL), Storage, and Functions as production-grade infrastructure, reducing MVP development time from weeks to hours.
* [ooples/token-optimizer-mcp](https://github.com/ooples/token-optimizer-mcp) ⭐ 3 | 🐛 6 | 🌐 TypeScript | 📅 2025-10-24 📇 🏠 ☁️ 🍎 🪟 🐧 - Intelligent token optimization achieving 95%+ reduction through caching, compression, and 80+ smart tools for API optimization, code analysis, and real-time monitoring.
* [deploy-mcp/deploy-mcp](https://github.com/alexpota/deploy-mcp) ⭐ 2 | 🐛 2 | 🌐 TypeScript | 📅 2025-10-20 📇 ☁️ 🏠 - Universal deployment tracker for AI assistants with live status badges and deployment monitoring
* [flipt-io/mcp-server-flipt](https://github.com/flipt-io/mcp-server-flipt) ⭐ 2 | 🐛 3 | 🌐 TypeScript | 📅 2025-09-30 📇 🏠 - Enable AI assistants to interact with your feature flags in [Flipt](https://flipt.io).
* [mattjegan/swarmia-mcp](https://github.com/mattjegan/swarmia-mcp) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2025-09-13 🐍 🏠 🍎 🐧 - Read-only MCP server to help gather metrics from [Swarmia](origin/swarmia.com) for quick reporting.
* [neilberkman/editorconfig\_mcp](https://github.com/neilberkman/editorconfig_mcp) ⭐ 2 | 🐛 1 | 🌐 JavaScript | 📅 2025-06-17 📇 🏠 - Formats files using `.editorconfig` rules, acting as a proactive formatting gatekeeper to ensure AI-generated code adheres to project-specific formatting standards from the start.
* [Wooonster/hocr\_mcp\_server](https://github.com/Wooonster/hocr_mcp_server) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2025-08-17 🐍 🏠 – A fastAPI-based FastMCP server with a Vue frontend that sends uploaded images to VLM via the MCP to quickly extract handwritten mathematical formulas as clean LaTeX code.
* [davidlin2k/pox-mcp-server](https://github.com/davidlin2k/pox-mcp-server) ⭐ 1 | 🐛 4 | 🌐 Python | 📅 2025-03-24 🐍 🏠 - MCP server for the POX SDN controller to provides network control and management capabilities.
* [wyattjoh/jsr-mcp](https://github.com/wyattjoh/jsr-mcp) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2025-08-11 📇 ☁️ - Model Context Protocol server for the JSR (JavaScript Registry)
* [davidan90/time-node-mcp](https://github.com/davidan90/time-node-mcp) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2025-08-11 📇 🏠 - Timezone-aware date and time operations with support for IANA timezones, timezone conversion, and Daylight Saving Time handling.
* [Inspizzz/jetbrains-datalore-mcp](https://github.com/inspizzz/jetbrains-datalore-mcp) 🐍 ☁️ - MCP server for interacting with cloud deployments of Jetbrains Datalore platform. Fully incorporated Datalore API ( run, run interactively, get run data, fetch files )

### 🔒 <a name="delivery"></a>Delivery

* [https://github.com/jordandalton/doordash-mcp-server](https://github.com/JordanDalton/DoorDash-MCP-Server) ⭐ 13 | 🐛 2 | 🌐 TypeScript | 📅 2025-04-16 🐍 – DoorDash Delivery (Unofficial)

### 🧮 <a name="data-science-tools"></a>Data Science Tools

Integrations and tools designed to simplify data exploration, analysis and enhance data science workflows.

* [mckinsey/vizro-mcp](https://github.com/mckinsey/vizro/tree/main/vizro-mcp) ⭐ 3,446 | 🐛 50 | 🌐 Python | 📅 2025-10-23 🎖️ 🐍 🏠 - Tools and templates to create validated and maintainable data charts and dashboards.
* [zcaceres/markdownify-mcp](https://github.com/zcaceres/markdownify-mcp) ⭐ 2,214 | 🐛 13 | 🌐 TypeScript | 📅 2025-09-02 📇 🏠 - An MCP server to convert almost any file or web content into Markdown
* [datalayer/jupyter-mcp-server](https://github.com/datalayer/jupyter-mcp-server) ⭐ 727 | 🐛 11 | 🌐 Python | 📅 2025-10-23 🐍 🏠 - Model Context Protocol (MCP) Server for Jupyter.
* [DataEval/dingo](https://github.com/DataEval/dingo) ⭐ 504 | 🐛 6 | 🌐 JavaScript | 📅 2025-10-23 🎖️ 🐍 🏠 🍎 🪟 🐧 - MCP server for the Dingo: a comprehensive data quality evaluation tool. Server Enables interaction with Dingo's rule-based and LLM-based evaluation capabilities and rules\&prompts listing.
* [reading-plus-ai/mcp-server-data-exploration](https://github.com/reading-plus-ai/mcp-server-data-exploration) ⭐ 498 | 🐛 8 | 🌐 Python | 📅 2025-03-22 🐍 ☁️ - Enables autonomous data exploration on .csv-based datasets, providing intelligent insights with minimal effort.
* [jjsantos01/jupyter-notebook-mcp](https://github.com/jjsantos01/jupyter-notebook-mcp) ⭐ 111 | 🐛 3 | 🌐 Jupyter Notebook | 📅 2025-04-02 🐍 🏠 - connects Jupyter Notebook to Claude AI, allowing Claude to directly interact with and control Jupyter Notebooks.
* [ChronulusAI/chronulus-mcp](https://github.com/ChronulusAI/chronulus-mcp) ⭐ 103 | 🐛 4 | 🌐 Python | 📅 2025-07-19 🐍 ☁️ - Predict anything with Chronulus AI forecasting and prediction agents.
* [kdqed/zaturn](https://github.com/kdqed/zaturn) ⭐ 64 | 🐛 0 | 🌐 Python | 📅 2025-10-21 🐍 🏠 🪟 🐧 🍎 - Link multiple data sources (SQL, CSV, Parquet, etc.) and ask AI to analyze the data for insights and visualizations.
* [optuna/optuna-mcp](https://github.com/optuna/optuna-mcp) ⭐ 63 | 🐛 0 | 🌐 Python | 📅 2025-10-02 🎖️ 🐍 🏠 🐧 🍎 - Official MCP server enabling seamless orchestration of hyperparameter search and other optimization tasks with [Optuna](https://optuna.org/).
* [arrismo/kaggle-mcp](https://github.com/arrismo/kaggle-mcp) ⭐ 25 | 🐛 1 | 🌐 Python | 📅 2025-08-25 🐍 ☁️ - Connects to Kaggle, ability to download and analyze datasets.
* [HumanSignal/label-studio-mcp-server](https://github.com/HumanSignal/label-studio-mcp-server) ⭐ 22 | 🐛 1 | 🌐 Python | 📅 2025-05-30 🎖️ 🐍 ☁️ 🪟 🐧 🍎 - Create, manage, and automate Label Studio projects, tasks, and predictions for data labeling workflows.
* [subelsky/bundler\_mcp](https://github.com/subelsky/bundler_mcp) ⭐ 19 | 🐛 0 | 🌐 Ruby | 📅 2025-06-29 💎 🏠 - Enables agents to query local information about dependencies in a Ruby project's `Gemfile`.
* [growthbook/growthbook-mcp](https://github.com/growthbook/growthbook-mcp) ⭐ 15 | 🐛 8 | 🌐 TypeScript | 📅 2025-09-19 🎖️ 📇 🏠 🪟 🐧 🍎 — Tools for creating and interacting with GrowthBook feature flags and experiments.
* [phisanti/MCPR](https://github.com/phisanti/MCPR) ⭐ 12 | 🐛 2 | 🌐 R | 📅 2025-10-21 🏠 🍎 🪟 🐧 - Model Context Protocol for R: enables AI agents to participate in interactive live R sessions.
* [Bright-L01/networkx-mcp-server](https://github.com/Bright-L01/networkx-mcp-server) ⭐ 9 | 🐛 1 | 🌐 Python | 📅 2025-10-20 🐍 🏠 - The first NetworkX integration for Model Context Protocol, enabling graph analysis and visualization directly in AI conversations. Supports 13 operations including centrality algorithms, community detection, PageRank, and graph visualization.
* [avisangle/calculator-server](https://github.com/avisangle/calculator-server) ⭐ 0 | 🐛 1 | 🌐 Go | 📅 2025-09-19 🏎️ 🏠 - A comprehensive Go-based MCP server for mathematical computations, implementing 13 mathematical tools across basic arithmetic, advanced functions, statistical analysis, unit conversions, and financial calculations.

### 📟 <a name="embedded-system"></a>Embedded System

Provides access to documentation and shortcuts for working on embedded devices.

* [stack-chan/stack-chan](https://github.com/stack-chan/stack-chan) ⭐ 963 | 🐛 28 | 🌐 TypeScript | 📅 2025-10-22 📇 📟 - A JavaScript-driven M5Stack-embedded super-kawaii robot with MCP server functionality for AI-controlled interactions and emotions.
* [horw/esp-mcp](https://github.com/horw/esp-mcp) ⭐ 113 | 🐛 32 | 🌐 Python | 📅 2025-07-02 📟 - Workflow for fixing build issues in ESP32 series chips using ESP-IDF.
* [kukapay/modbus-mcp](https://github.com/kukapay/modbus-mcp) ⭐ 18 | 🐛 0 | 🌐 Python | 📅 2025-05-12 🐍 📟 - An MCP server that standardizes and contextualizes industrial Modbus data.
* [kukapay/opcua-mcp](https://github.com/kukapay/opcua-mcp) ⭐ 18 | 🐛 3 | 🌐 Python | 📅 2025-05-22 🐍 📟 - An MCP server that connects to OPC UA-enabled industrial systems.
* [yoelbassin/gnuradioMCP](https://github.com/yoelbassin/gnuradioMCP) ⭐ 18 | 🐛 0 | 🌐 Python | 📅 2025-08-16 🐍 📟 🏠 - An MCP server for GNU Radio that enables LLMs to autonomously create and modify RF `.grc` flowcharts.

### 📂 <a name="file-systems"></a>File Systems

Provides direct access to local file systems with configurable permissions. Enables AI models to read, write, and manage files within specified directories.

* [microsoft/markitdown](https://github.com/microsoft/markitdown/tree/main/packages/markitdown-mcp) ⭐ 82,043 | 🐛 364 | 🌐 Python | 📅 2025-10-20 🎖️ 🐍 🏠 - MCP tool access to MarkItDown -- a library that converts many file formats (local or remote) to Markdown for LLM consumption.
* [modelcontextprotocol/server-filesystem](https://github.com/modelcontextprotocol/servers/tree/main/src/filesystem) ⭐ 71,117 | 🐛 277 | 🌐 TypeScript | 📅 2025-10-24 📇 🏠 - Direct local file system access.
* [mickaelkerjean/filestash](https://github.com/mickael-kerjean/filestash/tree/master/server/plugin/plg_handler_mcp) ⭐ 12,912 | 🐛 45 | 🌐 JavaScript | 📅 2025-10-20 🏎️ ☁️ - Remote Storage Access: SFTP, S3, FTP, SMB, NFS, WebDAV, GIT, FTPS, gcloud, azure blob, sharepoint, etc.
* [mark3labs/mcp-filesystem-server](https://github.com/mark3labs/mcp-filesystem-server) ⭐ 537 | 🐛 16 | 🌐 Go | 📅 2025-09-04 🏎️ 🏠 - Golang implementation for local file system access.
* [cyberchitta/llm-context.py](https://github.com/cyberchitta/llm-context.py) ⭐ 280 | 🐛 4 | 🌐 Python | 📅 2025-10-10 🐍 🏠 - Share code context with LLMs via MCP or clipboard
* [mamertofabian/mcp-everything-search](https://github.com/mamertofabian/mcp-everything-search) ⭐ 256 | 🐛 13 | 🌐 Python | 📅 2025-10-20 🐍 🏠 🪟 - Fast Windows file search using Everything SDK
* [isaacphi/mcp-gdrive](https://github.com/isaacphi/mcp-gdrive) ⭐ 222 | 🐛 10 | 🌐 TypeScript | 📅 2025-05-07 📇 ☁️ - Model Context Protocol (MCP) Server for reading from Google Drive and editing Google Sheets.
* [filesystem@quarkiverse/quarkus-mcp-servers](https://github.com/quarkiverse/quarkus-mcp-servers/tree/main/filesystem) ⭐ 172 | 🐛 24 | 🌐 Java | 📅 2025-07-28 ☕ 🏠 - A filesystem allowing for browsing and editing files implemented in Java using Quarkus. Available as jar or native image.
* [8b-is/smart-tree](https://github.com/8b-is/smart-tree) ⭐ 164 | 🐛 1 | 🌐 Rust | 📅 2025-10-03 🦀 🏠 🍎 🪟 🐧 - AI-native directory visualization with semantic analysis, ultra-compressed formats for AI consumption, and 10x token reduction. Supports quantum-semantic mode with intelligent file categorization.
* [Xuanwo/mcp-server-opendal](https://github.com/Xuanwo/mcp-server-opendal) ⭐ 33 | 🐛 2 | 🌐 Python | 📅 2025-04-10 🐍 🏠 ☁️ - Access any storage with Apache OpenDAL™
* [exoticknight/mcp-file-merger](https://github.com/exoticknight/mcp-file-merger) ⭐ 23 | 🐛 0 | 🌐 JavaScript | 📅 2025-09-06 🏎️ 🏠 - File merger tool, suitable for AI chat length limits.
* [jeannier/homebrew-mcp](https://github.com/jeannier/homebrew-mcp) ⭐ 17 | 🐛 3 | 🌐 Python | 📅 2025-06-23 🐍 🏠 🍎 - Control your macOS Homebrew setup using natural language via this MCP server. Simply manage your packages, or ask for suggestions, troubleshoot brew issues etc.
* [hmk/box-mcp-server](https://github.com/hmk/box-mcp-server) ⭐ 10 | 🐛 2 | 🌐 JavaScript | 📅 2025-08-22 📇 ☁️ - Box integration for listing, reading and searching files
* [box/mcp-server-box-remote](https://github.com/box/mcp-server-box-remote/) ⭐ 0 | 🐛 0 | 📅 2025-09-20 🎖️ ☁️ - The Box MCP server allows third party AI agents to securely and seamlessly access Box content and use tools such as search, asking questions from files and folders, and data extraction.

### 💰 <a name="finance--fintech"></a>Finance & Fintech

* [mcpdotdirect/evm-mcp-server](https://github.com/mcpdotdirect/evm-mcp-server) ⭐ 334 | 🐛 6 | 🌐 TypeScript | 📅 2025-07-29 📇 ☁️ - Comprehensive blockchain services for 30+ EVM networks, supporting native tokens, ERC20, NFTs, smart contracts, transactions, and ENS resolution.
* [longportapp/openapi](https://github.com/longportapp/openapi/tree/main/mcp) ⭐ 308 | 🐛 67 | 🌐 Rust | 📅 2025-10-23 - 🐍 ☁️ - LongPort OpenAPI provides real-time stock market data, provides AI access analysis and trading capabilities through MCP.
* [base/base-mcp](https://github.com/base/base-mcp) ⭐ 303 | 🐛 32 | 🌐 TypeScript | 📅 2025-06-17 🎖️ 📇 ☁️ - Base Network integration for onchain tools, allowing interaction with Base Network and Coinbase API for wallet management, fund transfers, smart contracts, and DeFi operations
* [ferdousbhai/investor-agent](https://github.com/ferdousbhai/investor-agent) ⭐ 277 | 🐛 0 | 🌐 Python | 📅 2025-09-21 🐍 ☁️ - Yahoo Finance integration to fetch stock market data including options recommendations
* [armorwallet/armor-crypto-mcp](https://github.com/armorwallet/armor-crypto-mcp) ⭐ 182 | 🐛 2 | 🌐 Python | 📅 2025-07-29 🐍 ☁️ - MCP to interface with multiple blockchains, staking, DeFi, swap, bridging, wallet management, DCA, Limit Orders, Coin Lookup, Tracking and more.
* [polygon-io/mcp\_polygon)](https://github.com/polygon-io/mcp_polygon) ⭐ 180 | 🐛 11 | 🌐 Python | 📅 2025-10-15) 🐍 ☁️ -  An MCP server that provides access to [Polygon.io](https://polygon.io/) financial market data APIs for stocks, indices, forex, options, and more.
* [XeroAPI/xero-mcp-server](https://github.com/XeroAPI/xero-mcp-server) ⭐ 142 | 🐛 14 | 🌐 TypeScript | 📅 2025-05-18 📇 ☁️ – An MCP server that integrates with Xero's API, allowing for standardized access to Xero's accounting and business features.
* [aaronjmars/web3-research-mcp](https://github.com/aaronjmars/web3-research-mcp) ⭐ 137 | 🐛 0 | 🌐 TypeScript | 📅 2025-06-05 📇 ☁️ - Deep Research for crypto - free & fully local
* [doggybee/mcp-server-ccxt](https://github.com/doggybee/mcp-server-ccxt) ⭐ 114 | 🐛 2 | 🌐 TypeScript | 📅 2025-06-03 📇 ☁️ - An MCP server for accessing real-time crypto market data and trading via 20+ exchanges using the CCXT library. Supports spot, futures, OHLCV, balances, orders, and more.
* [ariadng/metatrader-mcp-server](https://github.com/ariadng/metatrader-mcp-server) ⭐ 109 | 🐛 6 | 🌐 Python | 📅 2025-10-09 🐍 🏠 🪟 - Enable AI LLMs to execute trades using MetaTrader 5 platform
* [QuantGeekDev/coincap-mcp](https://github.com/QuantGeekDev/coincap-mcp) ⭐ 88 | 🐛 7 | 🌐 TypeScript | 📅 2025-01-30 📇 ☁️ - Real-time cryptocurrency market data integration using CoinCap's public API, providing access to crypto prices and market information without API keys
* [kukapay/freqtrade-mcp](https://github.com/kukapay/freqtrade-mcp) ⭐ 87 | 🐛 5 | 🌐 Python | 📅 2025-04-17 🐍 ☁️ - An MCP server that integrates with the Freqtrade cryptocurrency trading bot.
* [kukapay/crypto-indicators-mcp](https://github.com/kukapay/crypto-indicators-mcp) ⭐ 86 | 🐛 5 | 🌐 JavaScript | 📅 2025-03-27 🐍 ☁️ - An MCP server providing a range of cryptocurrency technical analysis indicators and strategie.
* [berlinbra/alpha-vantage-mcp](https://github.com/berlinbra/alpha-vantage-mcp) ⭐ 77 | 🐛 3 | 🌐 Python | 📅 2025-10-22 🐍 ☁️ - Alpha Vantage API integration to fetch both stock and crypto information
* [OctagonAI/octagon-mcp-server](https://github.com/OctagonAI/octagon-mcp-server) ⭐ 74 | 🐛 4 | 🌐 JavaScript | 📅 2025-07-21 🐍 ☁️ - Octagon AI Agents to integrate private and public market data
* [alchemy/alchemy-mcp-server](https://github.com/alchemyplatform/alchemy-mcp-server) ⭐ 69 | 🐛 6 | 🌐 TypeScript | 📅 2025-09-18 🎖️ 📇 ☁️ - Allow AI agents to interact with Alchemy's blockchain APIs.
* [bankless/onchain-mcp](https://github.com/Bankless/onchain-mcp/) ⭐ 68 | 🐛 5 | 🌐 TypeScript | 📅 2025-10-20 📇 ☁️ - Bankless Onchain API to interact with smart contracts, query transaction and token information
* [narumiruna/yfinance-mcp](https://github.com/narumiruna/yfinance-mcp) ⭐ 65 | 🐛 1 | 🌐 Python | 📅 2025-10-21 🐍 ☁️ - An MCP server that uses yfinance to obtain information from Yahoo Finance.
* [heurist-network/heurist-mesh-mcp-server](https://github.com/heurist-network/heurist-mesh-mcp-server) ⭐ 60 | 🐛 6 | 🌐 Python | 📅 2025-09-13 🎖️ ⛅️ 🏠 🐍 - Access specialized web3 AI agents for blockchain analysis, smart contract security auditing, token metrics evaluation, and on-chain interactions through the Heurist Mesh network. Provides comprehensive tools for DeFi analysis, NFT valuation, and transaction monitoring across multiple blockchains
* [kukapay/cryptopanic-mcp-server](https://github.com/kukapay/cryptopanic-mcp-server) ⭐ 56 | 🐛 3 | 🌐 Python | 📅 2025-06-18 🐍 ☁️ - Providing latest cryptocurrency news to AI agents, powered by CryptoPanic.
* [HuggingAGI/mcp-baostock-server](https://github.com/HuggingAGI/mcp-baostock-server) ⭐ 52 | 🐛 2 | 🌐 Python | 📅 2025-04-08 🐍 ☁️ - MCP server based on baostock, providing access and analysis capabilities for Chinese stock market data.
* [QuantConnect/mcp-server](https://github.com/QuantConnect/mcp-server) ⭐ 45 | 🐛 7 | 🌐 Python | 📅 2025-10-03 🐍 ☁️ – A Dockerized Python MCP server that bridges your local AI (e.g., Claude Desktop, etc) with the QuantConnect API—empowering you to create projects, backtest strategies, manage collaborators, and deploy live-trading workflows directly via natural-language prompts.
* [zlinzzzz/finData-mcp-server](https://github.com/zlinzzzz/finData-mcp-server) ⭐ 45 | 🐛 2 | 🌐 Python | 📅 2025-05-09 🐍 ☁️ - An MCP server for accessing professional financial data, supporting multiple data providers such as Tushare.
* [ferdousbhai/tasty-agent](https://github.com/ferdousbhai/tasty-agent) ⭐ 43 | 🐛 0 | 🌐 Python | 📅 2025-10-14 🐍 ☁️ - Tastyworks API integration to handle trading activities on Tastytrade
* [anjor/coinmarket-mcp-server](https://github.com/anjor/coinmarket-mcp-server) ⭐ 42 | 🐛 2 | 🌐 Python | 📅 2025-06-24 🐍 ☁️ - Coinmarket API integration to fetch cryptocurrency listings and quotes
* [kukapay/crypto-feargreed-mcp](https://github.com/kukapay/crypto-feargreed-mcp) ⭐ 42 | 🐛 4 | 🌐 Python | 📅 2025-05-10 🐍 ☁️ -  Providing real-time and historical Crypto Fear & Greed Index data.
* [kukapay/whale-tracker-mcp](https://github.com/kukapay/whale-tracker-mcp) ⭐ 41 | 🐛 4 | 🌐 Python | 📅 2025-05-07 🐍 ☁️ -  A mcp server for tracking cryptocurrency whale transactions.
* [twelvedata/mcp](https://github.com/twelvedata/mcp) ⭐ 39 | 🐛 3 | 🌐 Python | 📅 2025-07-31 🐍 ☁️ - Interact with [Twelve Data](https://twelvedata.com) APIs to access real-time and historical financial market data for your AI agents.
* [kukapay/crypto-sentiment-mcp](https://github.com/kukapay/crypto-sentiment-mcp) ⭐ 37 | 🐛 2 | 🌐 Python | 📅 2025-03-27 🐍 ☁️ - An MCP server that delivers cryptocurrency sentiment analysis to AI agents.
* [Trade-Agent/trade-agent-mcp](https://github.com/Trade-Agent/trade-agent-mcp.git) ⭐ 37 | 🐛 0 | 📅 2025-10-01 🎖️ ☁️ - Trade stocks and crypto on common brokerages (Robinhood, E\*Trade, Coinbase, Kraken) via Trade Agent's MCP server.
* [getAlby/mcp](https://github.com/getAlby/mcp) ⭐ 33 | 🐛 0 | 🌐 TypeScript | 📅 2025-07-16 🎖️ 📇 ☁️ 🏠 - Connect any bitcoin lightning wallet to your agent to send and receive instant payments globally.
* [laukikk/alpaca-mcp](https://github.com/laukikk/alpaca-mcp) ⭐ 32 | 🐛 2 | 🌐 Python | 📅 2025-07-14 🐍 ☁️ - An MCP Server for the Alpaca trading API to manage stock and crypto portfolios, place trades, and access market data.
* [kukapay/dune-analytics-mcp](https://github.com/kukapay/dune-analytics-mcp) ⭐ 31 | 🐛 4 | 🌐 Python | 📅 2025-05-04 🐍 ☁️ -  A mcp server that bridges Dune Analytics data to AI agents.
* [kukapay/uniswap-trader-mcp](https://github.com/kukapay/uniswap-trader-mcp) ⭐ 31 | 🐛 2 | 🌐 JavaScript | 📅 2025-05-07 🐍 ☁️ -  An MCP server that delivers real-time token prices from Uniswap V3 across multiple chains.
* [minhyeoky/mcp-server-ledger](https://github.com/minhyeoky/mcp-server-ledger) ⭐ 31 | 🐛 3 | 🌐 Python | 📅 2025-10-19 🐍 🏠 -  A ledger-cli integration for managing financial transactions and generating reports.
* [wowinter13/solscan-mcp](https://github.com/wowinter13/solscan-mcp) ⭐ 31 | 🐛 0 | 🌐 Rust | 📅 2025-08-15 🦀 🏠 - An MCP tool for querying Solana transactions using natural language with Solscan API.
* [coinpaprika/dexpaprika-mcp](https://github.com/coinpaprika/dexpaprika-mcp) ⭐ 28 | 🐛 3 | 🌐 JavaScript | 📅 2025-10-14 🎖️ 📇 ☁️ 🍎 🪟 🐧 - Coinpaprika's DexPaprika MCP server exposes high-performance [DexPaprika API](https://docs.dexpaprika.com) covering 20+ chains and 5M+ tokens with real time pricing, liquidity pool data & historical OHLCV data, providing AI agents standardized access to comprehensive market data through Model Context Protocol.
* [SaintDoresh/YFinance-Trader-MCP-ClaudeDesktop](https://github.com/SaintDoresh/YFinance-Trader-MCP-ClaudeDesktop.git) ⭐ 27 | 🐛 0 | 🌐 Python | 📅 2025-08-11 🐍 ☁️ - An MCP tool that provides stock market data and analysis using the Yahoo Finance API.
* [pwh-pwh/coin-mcp-server](https://github.com/pwh-pwh/coin-mcp-server) ⭐ 26 | 🐛 2 | 🌐 TypeScript | 📅 2025-04-15 🐍 ☁️ -  Bitget API to fetch cryptocurrency price.
* [kukapay/hyperliquid-info-mcp](https://github.com/kukapay/hyperliquid-info-mcp) ⭐ 22 | 🐛 0 | 🌐 Python | 📅 2025-05-31 🐍 ☁️ - An MCP server that provides real-time data and insights from the Hyperliquid perp DEX for use in bots, dashboards, and analytics.
* [kukapay/jupiter-mcp](https://github.com/kukapay/jupiter-mcp) ⭐ 20 | 🐛 4 | 🌐 JavaScript | 📅 2025-06-14 🐍 ☁️ - An MCP server for executing token swaps on the Solana blockchain using Jupiter's new Ultra API.
* [codex-data/codex-mcp](https://github.com/Codex-Data/codex-mcp) ⭐ 18 | 🐛 2 | 🌐 TypeScript | 📅 2025-04-05 🎖️ 📇 ☁️ - [Codex API](https://www.codex.io) integration for real-time enriched blockchain and market data on 60+ networks
* [ferdousbhai/wsb-analyst-mcp](https://github.com/ferdousbhai/wsb-analyst-mcp) ⭐ 18 | 🐛 0 | 🌐 Python | 📅 2025-09-21 🐍 ☁️ - Reddit integration to analyze content on WallStreetBets community
* [openMF/mcp-mifosx](https://github.com/openMF/mcp-mifosx) ⭐ 17 | 🐛 1 | 🌐 Java | 📅 2025-10-23 ☁️ 🏠 -  A core banking integration for managing clients, loans, savings, shares, financial transactions and generating financial reports.
* [SaintDoresh/Crypto-Trader-MCP-ClaudeDesktop](https://github.com/SaintDoresh/Crypto-Trader-MCP-ClaudeDesktop.git) ⭐ 16 | 🐛 1 | 🌐 Python | 📅 2025-03-16 🐍 ☁️ - An MCP tool that provides cryptocurrency market data using the CoinGecko API.
* [janswist/mcp-dexscreener](https://github.com/janswist/mcp-dexscreener) ⭐ 15 | 🐛 2 | 🌐 JavaScript | 📅 2025-04-07 📇 ☁️ - Real-time on-chain market prices using open and free Dexscreener API
* [kukapay/rug-check-mcp](https://github.com/kukapay/rug-check-mcp) ⭐ 14 | 🐛 3 | 🌐 Python | 📅 2025-05-06 🐍 ☁️ - An MCP server that detects potential risks in Solana meme tokens.
* [kukapay/token-minter-mcp](https://github.com/kukapay/token-minter-mcp) ⭐ 14 | 🐛 4 | 🌐 JavaScript | 📅 2025-04-28 🐍 ☁️ -  An MCP server providing tools for AI agents to mint ERC-20 tokens across multiple blockchains.
* [bitteprotocol/mcp](https://github.com/BitteProtocol/mcp) ⭐ 13 | 🐛 1 | 🌐 TypeScript | 📅 2025-04-09 📇 - Bitte Protocol integration to run AI Agents on several blockchains.
* [chargebee/mcp](https://github.com/chargebee/agentkit/tree/main/modelcontextprotocol) ⭐ 13 | 🐛 3 | 🌐 TypeScript | 📅 2025-07-16 🎖️ 📇 ☁️ - MCP Server that connects AI agents to [Chargebee platform](https://www.chargebee.com/).
* [ahnlabio/bicscan-mcp](https://github.com/ahnlabio/bicscan-mcp) ⭐ 12 | 🐛 3 | 🌐 Python | 📅 2025-04-03 🎖️ 🐍 ☁️ - Risk score / asset holdings of EVM blockchain address (EOA, CA, ENS) and even domain names.
* [getalby/nwc-mcp-server](https://github.com/getalby/nwc-mcp-server) ⚠️ Archived 📇 🏠 - Bitcoin Lightning wallet integration powered by Nostr Wallet Connect
* [tatumio/blockchain-mcp](https://github.com/tatumio/blockchain-mcp) ⭐ 12 | 🐛 2 | 🌐 TypeScript | 📅 2025-08-08 ☁️ - MCP server for Blockchain Data. It provides access to Tatum's blockchain API across 130+ networks with tools including RPC Gateway and Blockchain Data insights.
* [ThomasMarches/substrate-mcp-rs](https://github.com/ThomasMarches/substrate-mcp-rs) ⭐ 11 | 🐛 0 | 🌐 Rust | 📅 2025-10-12 🦀 🏠 - An MCP server implementation to interact with Substrate-based blockchains. Built with Rust and interfacing the [subxt](https://github.com/paritytech/subxt) ⭐ 469 | 🐛 83 | 🌐 Rust | 📅 2025-10-22 crate.
* [kukapay/crypto-news-mcp](https://github.com/kukapay/crypto-news-mcp) ⭐ 10 | 🐛 2 | 🌐 Python | 📅 2025-05-06 🐍 ☁️ - An MCP server that provides real-time cryptocurrency news sourced from NewsData for AI agents.
* [kukapay/defi-yields-mcp](https://github.com/kukapay/defi-yields-mcp) ⭐ 10 | 🐛 3 | 🌐 Python | 📅 2025-04-19 🐍 ☁️ - An MCP server for AI agents to explore DeFi yield opportunities.
* [kukapay/hyperliquid-whalealert-mcp](https://github.com/kukapay/hyperliquid-whalealert-mcp) ⭐ 9 | 🐛 0 | 🌐 Python | 📅 2025-05-12 🐍 ☁️ - An MCP server that provides real-time whale alerts on Hyperliquid, flagging positions with a notional value exceeding $1 million.
* [kukapay/blockbeats-mcp](https://github.com/kukapay/blockbeats-mcp) ⭐ 8 | 🐛 2 | 🌐 Python | 📅 2025-05-06 🐍 ☁️ -  An MCP server that delivers blockchain news and in-depth articles from BlockBeats for AI agents.
* [kukapay/crypto-orderbook-mcp](https://github.com/kukapay/crypto-orderbook-mcp) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2025-05-07 🐍 ☁️ - Analyzing order book depth and imbalance across major crypto exchanges.
* [kukapay/crypto-portfolio-mcp](https://github.com/kukapay/crypto-portfolio-mcp) ⭐ 8 | 🐛 1 | 🌐 Python | 📅 2025-04-05 🐍 ☁️ - An MCP server for tracking and managing cryptocurrency portfolio allocations.
* [kukapay/binance-alpha-mcp](https://github.com/kukapay/binance-alpha-mcp) ⭐ 7 | 🐛 1 | 🌐 JavaScript | 📅 2025-05-14 🐍 ☁️ - An MCP server for tracking Binance Alpha trades, helping AI agents optimize alpha point accumulation.
* [kukapay/cointelegraph-mcp](https://github.com/kukapay/cointelegraph-mcp) ⭐ 7 | 🐛 3 | 🌐 Python | 📅 2025-04-11 🐍 ☁️ -  Providing real-time access to the latest news from Cointelegraph.
* [shareseer/shareseer-mcp-server](https://github.com/shareseer/shareseer-mcp-server) ⭐ 7 | 🐛 1 | 📅 2025-06-29 🏎️ ☁️ - MCP to Access SEC filings, financials & insider trading data in real time using [ShareSeer](https://shareseer.com)
* [JamesANZ/prediction-market-mcp](https://github.com/JamesANZ/prediction-market-mcp) ⭐ 7 | 🐛 0 | 🌐 TypeScript | 📅 2025-10-07 📇 ☁️ - An MCP server that provides real-time prediction market data from multiple platforms including Polymarket, PredictIt, and Kalshi. Enables AI assistants to query current odds, prices, and market information through a unified interface.
* [hive-intel/hive-crypto-mcp](https://github.com/hive-intel/hive-crypto-mcp) ⭐ 7 | 🐛 1 | 🌐 TypeScript | 📅 2025-09-08 📇 ☁️ 🏠 - Hive Intelligence: Ultimate cryptocurrency MCP for AI assistants with unified access to crypto, DeFi, and Web3 analytics
* [kukapay/crypto-rss-mcp](https://github.com/kukapay/crypto-rss-mcp) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2025-07-24 🐍 ☁️ - An MCP server that aggregates real-time cryptocurrency news from multiple RSS feeds.
* [kukapay/etf-flow-mcp](https://github.com/kukapay/etf-flow-mcp) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2025-04-25 🐍 ☁️ -  Delivering crypto ETF flow data to power AI agents' decision-making.
* [kukapay/funding-rates-mcp](https://github.com/kukapay/funding-rates-mcp) ⭐ 6 | 🐛 1 | 🌐 Python | 📅 2025-04-21 🐍 ☁️ - Providing real-time funding rate data across major crypto exchanges.
* [kukapay/pancakeswap-poolspy-mcp](https://github.com/kukapay/pancakeswap-poolspy-mcp) ⭐ 6 | 🐛 3 | 🌐 Python | 📅 2025-05-07 🐍 ☁️ -  An MCP server that tracks newly created pools on Pancake Swap.
* [kukapay/thegraph-mcp](https://github.com/kukapay/thegraph-mcp) ⭐ 6 | 🐛 4 | 🌐 Python | 📅 2025-07-31 🐍 ☁️ -  An MCP server that powers AI agents with indexed blockchain data from The Graph.
* [kukapay/chainlink-feeds-mcp](https://github.com/kukapay/chainlink-feeds-mcp) ⭐ 5 | 🐛 2 | 🌐 JavaScript | 📅 2025-07-24 📇 ☁️ -  Providing real-time access to Chainlink's decentralized on-chain price feeds.
* [kukapay/crypto-trending-mcp](https://github.com/kukapay/crypto-trending-mcp) ⭐ 5 | 🐛 1 | 🌐 Python | 📅 2025-07-24 🐍 ☁️ - Tracking the latest trending tokens on CoinGecko.
* [kukapay/pumpswap-mcp](https://github.com/kukapay/pumpswap-mcp) ⭐ 5 | 🐛 1 | 🌐 Python | 📅 2025-05-06 🐍 ☁️ - Enabling AI agents to interact with PumpSwap for real-time token swaps and automated on-chain trading.
* [kukapay/uniswap-poolspy-mcp](https://github.com/kukapay/uniswap-poolspy-mcp) ⭐ 5 | 🐛 3 | 🌐 Python | 📅 2025-03-27 🐍 ☁️ -  An MCP server that tracks newly created liquidity pools on Uniswap across multiple blockchains.
* [kukapay/wallet-inspector-mcp](https://github.com/kukapay/wallet-inspector-mcp) ⭐ 5 | 🐛 1 | 🌐 Python | 📅 2025-06-01 🐍 ☁️ -  An MCP server that empowers AI agents to inspect any wallet’s balance and onchain activity across major EVM chains and Solana chain.
* [mcpdotdirect/starknet-mcp-server](https://github.com/mcpdotdirect/starknet-mcp-server) ⭐ 5 | 🐛 0 | 🌐 TypeScript | 📅 2025-05-23 📇 ☁️ - Comprehensive Starknet blockchain integration with support for native tokens (ETH, STRK), smart contracts, StarknetID resolution, and token transfers.
* [RomThpt/xrpl-mcp-server](https://github.com/RomThpt/mcp-xrpl) ⭐ 5 | 🐛 1 | 🌐 TypeScript | 📅 2025-04-21 📇 ☁️ - MCP server for the XRP Ledger that provides access to account information, transaction history, and network data. Allows querying ledger objects, submitting transactions, and monitoring the XRPL network.
* [jjlabsio/korea-stock-mcp](https://github.com/jjlabsio/korea-stock-mcp) ⭐ 4 | 🐛 0 | 🌐 TypeScript | 📅 2025-10-15 📇 ☁️ - An MCP Server for Korean stock analysis using OPEN DART API and KRX API
* [kukapay/bridge-rates-mcp](https://github.com/kukapay/bridge-rates-mcp) ⭐ 4 | 🐛 2 | 🌐 JavaScript | 📅 2025-04-24 📇 ☁️ - Delivering real-time cross-chain bridge rates and optimal transfer routes to onchain AI agents.
* [kukapay/crypto-whitepapers-mcp](https://github.com/kukapay/crypto-whitepapers-mcp) ⭐ 4 | 🐛 3 | 🌐 Python | 📅 2025-04-19 🐍 ☁️ - Serving as a structured knowledge base of crypto whitepapers.
* [kukapay/sui-trader-mcp](https://github.com/kukapay/sui-trader-mcp) ⭐ 4 | 🐛 1 | 🌐 JavaScript | 📅 2025-05-10 📇 ☁️ - An MCP server designed for AI agents to perform optimal token swaps on the Sui blockchain.
* [kukapay/web3-jobs-mcp](https://github.com/kukapay/web3-jobs-mcp) ⭐ 4 | 🐛 1 | 🌐 Python | 📅 2025-06-02 🐍 ☁️ -  An MCP server that provides AI agents with real-time access to curated Web3 jobs.
* [zolo-ryan/MarketAuxMcpServer](https://github.com/Zolo-Ryan/MarketAuxMcpServer) ⭐ 4 | 🐛 1 | 🌐 TypeScript | 📅 2025-06-30 📇 ☁️ - MCP server for comprehensive market and financial news search with advanced filtering by symbols, industries, countries, and date ranges.
* [glaksmono/finbud-data-mcp](https://github.com/glaksmono/finbud-data-mcp/tree/main/packages/mcp-server) ⭐ 3 | 🐛 1 | 🌐 TypeScript | 📅 2025-06-21 📇 ☁️ 🏠 - Access comprehensive, real-time financial data (stocks, options, crypto, forex) via developer-friendly, AI-native APIs offering unbeatable value.
* [intentos-labs/beeper-mcp](https://github.com/intentos-labs/beeper-mcp) ⭐ 3 | 🐛 1 | 🌐 Python | 📅 2025-04-10 🐍 - Beeper provides transactions on BSC, including balance/token transfers, token swaps in Pancakeswap and beeper reward claims.
* [kukapay/blocknative-mcp](https://github.com/kukapay/blocknative-mcp) ⭐ 3 | 🐛 2 | 🌐 Python | 📅 2025-04-30 🐍 ☁️ -  Providing real-time gas price predictions across multiple blockchains, powered by Blocknative.
* [kukapay/crypto-liquidations-mcp](https://github.com/kukapay/crypto-liquidations-mcp) ⭐ 3 | 🐛 1 | 🌐 Python | 📅 2025-05-06 🐍 ☁️ - Streams real-time cryptocurrency liquidation events from Binance.
* [kukapay/crypto-pegmon-mcp](https://github.com/kukapay/crypto-pegmon-mcp) ⭐ 3 | 🐛 3 | 🌐 Python | 📅 2025-05-05 🐍 ☁️ -  Tracking stablecoin peg integrity across multiple blockchains.
* [kukapay/raydium-launchlab-mcp](https://github.com/kukapay/raydium-launchlab-mcp) ⭐ 3 | 🐛 0 | 🌐 JavaScript | 📅 2025-05-21 🐍 ☁️ - An MCP server that enables AI agents to launch, buy, and sell tokens on the Raydium Launchpad(aka LaunchLab).
* [QuentinCody/braintree-mcp-server](https://github.com/QuentinCody/braintree-mcp-server) ⭐ 3 | 🐛 1 | 🌐 Python | 📅 2025-05-20 🐍 - Unofficial PayPal Braintree payment gateway MCP Server for AI agents to process payments, manage customers, and handle transactions securely.
* [Regenerating-World/pix-mcp](https://github.com/Regenerating-World/pix-mcp) ⭐ 2 | 🐛 1 | 🌐 TypeScript | 📅 2025-08-27 📇 ☁️ - Generate Pix QR codes and copy-paste strings with fallback across multiple providers (Efí, Cielo, etc.) for Brazilian instant payments.
* [kukapay/chainlist-mcp](https://github.com/kukapay/chainlist-mcp) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2025-05-31 📇 ☁️ -  An MCP server that gives AI agents fast access to verified EVM chain information, including RPC URLs, chain IDs, explorers, and native tokens.
* [kukapay/dao-proposals-mcp](https://github.com/kukapay/dao-proposals-mcp) ⭐ 2 | 🐛 2 | 🌐 Python | 📅 2025-08-02 🐍 ☁️ - An MCP server that aggregates live governance proposals from major DAOs.
* [kukapay/token-revoke-mcp](https://github.com/kukapay/token-revoke-mcp) ⭐ 2 | 🐛 4 | 🌐 JavaScript | 📅 2025-03-28 🐍 ☁️ - An MCP server for checking and revoking ERC-20 token allowances across multiple blockchains.
* [kukapay/twitter-username-changes-mcp](https://github.com/kukapay/twitter-username-changes-mcp) ⭐ 2 | 🐛 3 | 🌐 Python | 📅 2025-04-14 🐍 ☁️ - An MCP server that tracks the historical changes of Twitter usernames.
* [kukapay/uniswap-price-mcp](https://github.com/kukapay/uniswap-price-mcp) ⭐ 2 | 🐛 1 | 🌐 JavaScript | 📅 2025-06-05 📇 ☁️ -  An MCP server that tracks newly created liquidity pools on Uniswap across multiple blockchains.
* [Wuye-AI/mcp-server-wuye-ai](https://github.com/wuye-ai/mcp-server-wuye-ai) ⭐ 1 | 🐛 1 | 📅 2025-10-24 🎖️ 📇 ☁️ - An MCP server that interact with capabilities of the CRIC Wuye AI platform, an intelligent assistant specifically for the property management industry.
* [araa47/jupiter-mcp](https://github.com/araa47/jupiter-mcp) ⭐ 0 | 🐛 2 | 🌐 Python | 📅 2025-08-13 🐍 ☁️ - Jupiter API Access (allow AI to Trade Tokens on Solana + Access Balances + Search Tokens + Create Limit Orders )
* [carsol/monarch-mcp-server](https://github.com/carsol/monarch-mcp-server) ⭐ 0 | 🐛 1 | 🌐 Python | 📅 2025-06-08 🐍 ☁️ - MCP server providing read-only access to Monarch Money financial data, enabling AI assistants to analyze transactions, budgets, accounts, and cashflow data with MFA support.
* [kukapay/crypto-projects-mcp](https://github.com/kukapay/crypto-projects-mcp) ⭐ 0 | 🐛 3 | 🌐 Python | 📅 2025-05-11 🐍 ☁️ - Providing cryptocurrency project data from Mobula.io to AI agents.
* [JamesANZ/evm-mcp](https://github.com/JamesANZ/evm-mcp) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2025-10-17 📇 ☁️ - An MCP server that provides complete access to Ethereum Virtual Machine (EVM) JSON-RPC methods. Works with any EVM-compatible node provider including Infura, Alchemy, QuickNode, local nodes, and more.
* [JamesANZ/bitcoin-mcp](https://github.com/JamesANZ/bitcoin-mcp) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2025-08-20 📇 🏠 - An MCP server that enables AI models to query the Bitcoin blockchain.
* [logotype/fixparser](https://gitlab.com/logotype/fixparser) 🎖 📇 ☁️ 🏠 📟  - FIX Protocol (send orders, market data, etc.) written in TypeScript.
* [tooyipjee/yahoofinance-mcp](https://github.com/tooyipjee/yahoofinance-mcp.git) 📇 ☁️ - TS version of yahoo finance mcp.

### 🎮 <a name="gaming"></a>Gaming

Integration with gaming related data, game engines, and services

* [CoderGamester/mcp-unity](https://github.com/CoderGamester/mcp-unity) ⭐ 1,041 | 🐛 5 | 🌐 C# | 📅 2025-09-21 #️⃣ 🏠 - MCP Server for Unity3d Game Engine integration for game development
* [Coding-Solo/godot-mcp](https://github.com/Coding-Solo/godot-mcp) ⭐ 1,004 | 🐛 26 | 🌐 JavaScript | 📅 2025-08-09 📇 🏠 - A MCP server for interacting with the Godot game engine, providing tools for editing, running, debugging, and managing scenes in Godot projects.
* [IvanMurzak/Unity-MCP](https://github.com/IvanMurzak/Unity-MCP) ⭐ 465 | 🐛 43 | 🌐 C# | 📅 2025-10-23 #️⃣ 🏠 🍎 🪟 🐧 - MCP Server for Unity Editor and for a game made with Unity
* [rishijatia/fantasy-pl-mcp](https://github.com/rishijatia/fantasy-pl-mcp/) ⭐ 63 | 🐛 2 | 🌐 Python | 📅 2025-08-15 🐍 ☁️ - An MCP server for real-time Fantasy Premier League data and analysis tools.
* [pab1ito/chess-mcp](https://github.com/pab1it0/chess-mcp) ⭐ 52 | 🐛 4 | 🌐 Python | 📅 2025-06-01 🐍 ☁️ - Access Chess.com player data, game records, and other public information through standardized MCP interfaces, allowing AI assistants to search and analyze chess information.
* [opgginc/opgg-mcp](https://github.com/opgginc/opgg-mcp) ⭐ 43 | 🐛 1 | 🌐 TypeScript | 📅 2025-10-09 📇 ☁️ - Access real-time gaming data across popular titles like League of Legends, TFT, and Valorant, offering champion analytics, esports schedules, meta compositions, and character statistics.
* [kkjdaniel/bgg-mcp](https://github.com/kkjdaniel/bgg-mcp) ⭐ 19 | 🐛 0 | 🌐 Go | 📅 2025-10-16 🏎️ ☁️ - An MCP server that enables interaction with board game related data via the BoardGameGeek API (XML API2).
* [jiayao/mcp-chess](https://github.com/jiayao/mcp-chess) ⭐ 13 | 🐛 3 | 🌐 Python | 📅 2025-05-05 🐍 🏠 - A MCP server playing chess against LLMs.
* [stefan-xyz/mcp-server-runescape](https://github.com/stefan-xyz/mcp-server-runescape) ⭐ 6 | 🐛 2 | 🌐 JavaScript | 📅 2025-04-30 📇 - An MCP server with tools for interacting with RuneScape (RS) and Old School RuneScape (OSRS) data, including item prices, player hiscores, and more.
* [sonirico/mpc-stockfish](https://github.com/sonirico/mcp-stockfish) ⭐ 3 | 🐛 1 | 🌐 Go | 📅 2025-06-29 - 🏎️ 🏠 🍎 🪟 🐧️ MCP server connecting AI systems to Stockfish chess engine.
* [ddsky/gamebrain-api-clients](https://github.com/ddsky/gamebrain-api-clients) ⭐ 2 | 🐛 1 | 🌐 Java | 📅 2025-07-04 ☁️ - Search and discover hundreds of thousands of video games on any platform through the [GameBrain API](https://gamebrain.co/api).
* [tomholford/mcp-tic-tac-toe](https://github.com/tomholford/mcp-tic-tac-toe) ⭐ 2 | 🐛 0 | 🌐 Go | 📅 2025-07-11 🏎️ 🏠 - Play Tic Tac Toe against an AI opponent using this MCP server.

### 🧠 <a name="knowledge--memory"></a>Knowledge & Memory

Persistent memory storage using knowledge graph structures. Enables AI models to maintain and query structured information across sessions.

* [modelcontextprotocol/server-memory](https://github.com/modelcontextprotocol/servers/tree/main/src/memory) ⭐ 71,117 | 🐛 277 | 🌐 TypeScript | 📅 2025-10-24 📇 🏠 - Knowledge graph-based persistent memory system for maintaining context
* [upstash/context7](https://github.com/upstash/context7) ⭐ 34,821 | 🐛 100 | 🌐 JavaScript | 📅 2025-10-23 📇 ☁️ - Up-to-date code documentation for LLMs and AI code editors.
* [topoteretes/cognee](https://github.com/topoteretes/cognee/tree/dev/cognee-mcp) ⭐ 7,762 | 🐛 27 | 🌐 Python | 📅 2025-10-23 📇 🏠 - Memory manager for AI apps and Agents using various graph and vector stores and allowing ingestion from 30+ data sources
* [chatmcp/mcp-server-chatsum](https://github.com/chatmcp/mcp-server-chatsum) ⭐ 1,019 | 🐛 7 | 🌐 TypeScript | 📅 2024-12-04 - Query and summarize your chat messages with AI prompts.
* [apecloud/ApeRAG](https://github.com/apecloud/ApeRAG) ⭐ 877 | 🐛 50 | 🌐 Python | 📅 2025-10-16 🐍 ☁️ 🏠 - Production-ready RAG platform combining Graph RAG, vector search, and full-text search. Best choice for building your own Knowledge Graph and for Context Engineering
* [mem0ai/mem0-mcp](https://github.com/mem0ai/mem0-mcp) ⭐ 491 | 🐛 11 | 🌐 Python | 📅 2025-09-15 🐍 🏠 - A Model Context Protocol server for Mem0 that helps manage coding preferences and patterns, providing tools for storing, retrieving and semantically handling code implementations, best practices and technical documentation in IDEs like Cursor and Windsurf
* [graphlit-mcp-server](https://github.com/graphlit/graphlit-mcp-server) ⭐ 368 | 🐛 3 | 🌐 TypeScript | 📅 2025-10-07 📇 ☁️ - Ingest anything from Slack, Discord, websites, Google Drive, Linear or GitHub into a Graphlit project - and then search and retrieve relevant knowledge within an MCP client like Cursor, Windsurf or Cline.
* [CheMiguel23/MemoryMesh](https://github.com/CheMiguel23/MemoryMesh) ⭐ 308 | 🐛 8 | 🌐 TypeScript | 📅 2025-01-29 📇 🏠 - Enhanced graph-based memory with a focus on AI role-play and story generation
* [hannesrudolph/mcp-ragdocs](https://github.com/hannesrudolph/mcp-ragdocs) ⭐ 235 | 🐛 3 | 🌐 TypeScript | 📅 2025-07-18 🐍 🏠 - An MCP server implementation that provides tools for retrieving and processing documentation through vector search, enabling AI assistants to augment their responses with relevant documentation context
* [GistPad-MCP](https://github.com/lostintangent/gistpad-mcp) ⭐ 163 | 🐛 2 | 🌐 TypeScript | 📅 2025-07-07 📇 🏠 - Use GitHub Gists to manage and access your personal knowledge, daily notes, and reusable prompts. This acts as a companion to <https://gistpad.dev> and the [GistPad VS Code extension](https://aka.ms/gistpad).
* [0xshellming/mcp-summarizer](https://github.com/0xshellming/mcp-summarizer) ⭐ 136 | 🐛 7 | 🌐 JavaScript | 📅 2025-02-28 📕 ☁️ - AI Summarization MCP Server, Support for multiple content types: Plain text, Web pages, PDF documents, EPUB books, HTML content
* [kaliaboi/mcp-zotero](https://github.com/kaliaboi/mcp-zotero) ⭐ 135 | 🐛 11 | 🌐 TypeScript | 📅 2025-02-04 📇 ☁️ - A connector for LLMs to work with collections and sources on your Zotero Cloud
* [jinzcdev/markmap-mcp-server](https://github.com/jinzcdev/markmap-mcp-server) ⭐ 128 | 🐛 4 | 🌐 TypeScript | 📅 2025-06-12 📇 🏠 - An MCP server built on [markmap](https://github.com/markmap/markmap) ⭐ 11,949 | 🐛 53 | 🌐 TypeScript | 📅 2025-06-12 that converts **Markdown** to interactive **mind maps**. Supports multi-format exports (PNG/JPG/SVG), live browser preview, one-click Markdown copy, and dynamic visualization features.
* [entanglr/zettelkasten-mcp](https://github.com/entanglr/zettelkasten-mcp) ⭐ 108 | 🐛 7 | 🌐 Python | 📅 2025-04-25 🐍 🏠 - A Model Context Protocol (MCP) server that implements the Zettelkasten knowledge management methodology, allowing you to create, link, and search atomic notes through Claude and other MCP-compatible clients.
* [pi22by7/In-Memoria](https://github.com/pi22by7/In-Memoria) ⭐ 81 | 🐛 2 | 🌐 Rust | 📅 2025-10-18 📇 🦀 🏠 🍎 🐧 🪟 - Persistent intelligence infrastructure for agentic development that gives AI coding assistants cumulative memory and pattern learning. Hybrid TypeScript/Rust implementation with local-first storage using SQLite + SurrealDB for semantic analysis and incremental codebase understanding.
* [ragieai/mcp-server](https://github.com/ragieai/ragie-mcp-server) ⭐ 79 | 🐛 1 | 🌐 JavaScript | 📅 2025-06-10 📇 ☁️ - Retrieve context from your [Ragie](https://www.ragie.ai) (RAG) knowledge base connected to integrations like Google Drive, Notion, JIRA and more.
* [pinecone-io/assistant-mcp](https://github.com/pinecone-io/assistant-mcp) ⭐ 37 | 🐛 1 | 🌐 Rust | 📅 2025-04-17 🎖️ 🦀 ☁️ - Connects to your Pinecone Assistant and gives the agent context from its knowledge engine.
* [unibaseio/membase-mcp](https://github.com/unibaseio/membase-mcp) ⭐ 14 | 🐛 1 | 🌐 Python | 📅 2025-05-14 📇 ☁️ - Save and query your agent memory in distributed way by Membase
* [JamesANZ/memory-mcp](https://github.com/JamesANZ/memory-mcp) ⭐ 8 | 🐛 0 | 🌐 TypeScript | 📅 2025-09-24 📇 🏠 - An MCP server that stores and retrieves memories from multiple LLMs using MongoDB. Provides tools for saving, retrieving, adding, and clearing conversation memories with timestamps and LLM identification.
* [JamesANZ/cross-llm-mcp](https://github.com/JamesANZ/cross-llm-mcp) ⭐ 7 | 🐛 0 | 🌐 TypeScript | 📅 2025-10-17 📇 🏠 - An MCP server that enables cross-LLM communication and memory sharing, allowing different AI models to collaborate and share context across conversations.
* [cameronrye/openzim-mcp](https://github.com/cameronrye/openzim-mcp) ⭐ 5 | 🐛 8 | 🌐 Python | 📅 2025-10-17 🐍 🏠 - Modern, secure MCP server for accessing ZIM format knowledge bases offline. Enables AI models to search and navigate Wikipedia, educational content, and other compressed knowledge archives with smart retrieval, caching, and comprehensive API.
* [TechDocsStudio/biel-mcp](https://github.com/TechDocsStudio/biel-mcp) ⭐ 2 | 🐛 1 | 🌐 Python | 📅 2025-06-21 📇 ☁️ - Let AI tools like Cursor, VS Code, or Claude Desktop answer questions using your product docs. Biel.ai provides the RAG system and MCP server.
* [MWGMorningwood/Central-Memory-MCP](https://github.com/MWGMorningwood/Central-Memory-MCP) ⭐ 1 | 🐛 3 | 🌐 TypeScript | 📅 2025-10-20 📇 ☁️ - An Azure PaaS-hostable MCP server that provides a workspace-grounded knowledge graph for multiple developers using Azure Functions MCP triggers and Table storage.

### 🗺️ <a name="location-services"></a>Location Services

Location-based services and mapping tools. Enables AI models to work with geographic data, weather information, and location-based analytics.

* [QGIS MCP](https://github.com/jjsantos01/qgis_mcp) ⭐ 679 | 🐛 6 | 🌐 Python | 📅 2025-10-01 - connects QGIS Desktop to Claude AI through the MCP. This integration enables prompt-assisted project creation, layer loading, code execution, and more.
* [modelcontextprotocol/server-google-maps](https://github.com/modelcontextprotocol/servers-archived/tree/main/src/google-maps) ⚠️ Archived 📇 ☁️ - Google Maps integration for location services, routing, and place details
* [jagan-shanmugam/open-streetmap-mcp](https://github.com/jagan-shanmugam/open-streetmap-mcp) ⭐ 130 | 🐛 8 | 🌐 Python | 📅 2025-07-12 🐍 🏠 - An OpenStreetMap MCP server with location-based services and geospatial data.
* [mahdin75/gis-mcp](https://github.com/mahdin75/gis-mcp) ⭐ 62 | 🐛 3 | 🌐 Python | 📅 2025-09-29 🏠 – A Model Context Protocol (MCP) server implementation that connects Large Language Models (LLMs) to GIS operations using GIS libraries, enabling AI assistants to perform accurate geospatial operations and transformations.
* [mahdin75/geoserver-mcp](https://github.com/mahdin75/geoserver-mcp) ⭐ 40 | 🐛 1 | 🌐 Python | 📅 2025-06-30 🏠 – A Model Context Protocol (MCP) server implementation that connects LLMs to the GeoServer REST API, enabling AI assistants to interact with geospatial data and services.
* [SecretiveShell/MCP-timeserver](https://github.com/SecretiveShell/MCP-timeserver) ⭐ 39 | 🐛 4 | 🌐 Python | 📅 2025-01-07 🐍 🏠 - Access the time in any timezone and get the current local time
* [briandconnelly/mcp-server-ipinfo](https://github.com/briandconnelly/mcp-server-ipinfo) ⭐ 36 | 🐛 5 | 🌐 Python | 📅 2025-08-11 🐍 ☁️  - IP address geolocation and network information using IPInfo API
* [webcoderz/MCP-Geo](https://github.com/webcoderz/MCP-Geo) ⭐ 28 | 🐛 1 | 🌐 Python | 📅 2025-01-21 🐍 🏠 - Geocoding MCP server for nominatim, ArcGIS, Bing
* [TimLukaHorstmann/mcp-weather](https://github.com/TimLukaHorstmann/mcp-weather) ⭐ 27 | 🐛 0 | 🌐 TypeScript | 📅 2025-09-08 📇 ☁️  - Accurate weather forecasts via the AccuWeather API (free tier available).
* [isdaniel/mcp\_weather\_server](https://github.com/isdaniel/mcp_weather_server) ⭐ 23 | 🐛 1 | 🌐 Python | 📅 2025-10-21 🐍 ☁️ - Get weather information from <https://api.open-meteo.com> API.
* [kukapay/nearby-search-mcp](https://github.com/kukapay/nearby-search-mcp) ⭐ 19 | 🐛 5 | 🌐 Python | 📅 2025-03-27 🐍 ☁️ - An MCP server for nearby place searches with IP-based location detection.
* [stadiamaps/stadiamaps-mcp-server-ts](https://github.com/stadiamaps/stadiamaps-mcp-server-ts) ⭐ 18 | 🐛 1 | 🌐 TypeScript | 📅 2025-07-29 📇 ☁️ - A MCP server for Stadia Maps' Location APIs - Lookup addresses, places with geocoding, find time zones, create routes and static maps
* [devilcoder01/weather-mcp-server](https://github.com/devilcoder01/weather-mcp-server) ⭐ 17 | 🐛 2 | 🌐 Python | 📅 2025-08-21 🐍 ☁️ - Access real-time weather data for any location using the WeatherAPI.com API, providing detailed forecasts and current conditions.
* [ip2location/mcp-ip2location-io](https://github.com/ip2location/mcp-ip2location-io) ⭐ 12 | 🐛 1 | 🌐 Python | 📅 2025-07-16 🐍 ☁️  - Official IP2Location.io MCP server to obtain the geolocation, proxy and network information of an IP address utilizing IP2Location.io API.
* [iplocate/mcp-server-iplocate](https://github.com/iplocate/mcp-server-iplocate) ⭐ 11 | 🐛 1 | 🌐 JavaScript | 📅 2025-06-29 🎖️ 📇 🏠  - Look up IP address geolocation, network information, detect proxies and VPNs, and find abuse contact details using IPLocate.io
* [SaintDoresh/Weather-MCP-ClaudeDesktop](https://github.com/SaintDoresh/Weather-MCP-ClaudeDesktop.git) ⭐ 8 | 🐛 2 | 🌐 Python | 📅 2025-03-16 🐍 ☁️ - An MCP tool that provides real-time weather data, forecasts, and historical weather information using the OpenWeatherMap API.
* [rossshannon/Weekly-Weather-mcp](https://github.com/rossshannon/weekly-weather-mcp.git) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2025-04-10 🐍 ☁️ - Weekly Weather MCP server which returns 7 full days of detailed weather forecasts anywhere in the world.
* [ipfred/aiwen-mcp-server-geoip](https://github.com/ipfred/aiwen-mcp-server-geoip) ⭐ 4 | 🐛 0 | 🌐 JavaScript | 📅 2025-05-28 🐍 📇 ☁️ – MCP Server for the Aiwen IP Location, Get user network IP location, get IP details (country, province, city, lat, lon, ISP, owner, etc.)
* [ipfind/ipfind-mcp-server](https://github.com/ipfind/ipfind-mcp-server) ⭐ 2 | 🐛 4 | 🌐 JavaScript | 📅 2025-07-07 🐍 ☁️ - IP Address location service using the [IP Find](https://ipfind.com) API
* [cqtrinv/trinvmcp](https://github.com/cqtrinv/trinvmcp) ⭐ 1 | 🐛 0 | 🌐 JavaScript | 📅 2025-09-17 📇 ☁️ - Explore French communes and cadastral parcels based on name and surface
* [trackmage/trackmage-mcp-server](https://github.com/trackmage/trackmage-mcp-server) ⭐ 1 | 🐛 2 | 🌐 JavaScript | 📅 2025-06-09 📇 - Shipment tracking api and logistics management capabilities through the \[TrackMage API] (<https://trackmage.com/>)

### 🎯 <a name="marketing"></a>Marketing

Tools for creating and editing marketing content, working with web meta data, product positioning, and editing guides.

* [pipeboard-co/meta-ads-mcp](https://github.com/pipeboard-co/meta-ads-mcp) ⭐ 312 | 🐛 4 | 🌐 Python | 📅 2025-10-15 🐍 ☁️ 🏠 - Meta Ads automation that just works. Trusted by 10,000+ businesses to analyze performance, test creatives, optimize spend, and scale results — simply and reliably.
* [open-strategy-partners/osp\_marketing\_tools](https://github.com/open-strategy-partners/osp_marketing_tools) ⭐ 246 | 🐛 3 | 🌐 Python | 📅 2025-04-23 🐍 🏠 - A suite of marketing tools from Open Strategy Partners including writing style, editing codes, and product marketing value map creation.
* [gomarble-ai/facebook-ads-mcp-server](https://github.com/gomarble-ai/facebook-ads-mcp-server) ⭐ 173 | 🐛 1 | 🌐 Python | 📅 2025-08-21 🐍 ☁️ - MCP server acting as an interface to the Facebook Ads, enabling programmatic access to Facebook Ads data and management features.
* [gomarble-ai/google-ads-mcp-server](https://github.com/gomarble-ai/google-ads-mcp-server) ⭐ 72 | 🐛 3 | 🌐 Python | 📅 2025-07-09 🐍 ☁️ - MCP server acting as an interface to the Google Ads, enabling programmatic access to Google Ads data and management features.
* [stape-io/google-tag-manager-mcp-server](https://github.com/stape-io/google-tag-manager-mcp-server) ⭐ 62 | 🐛 3 | 🌐 TypeScript | 📅 2025-10-22 📇 ☁️ – This server supports remote MCP connections, includes built-in Google OAuth, and provide an interface to the Google Tag Manager API.
* [marketplaceadpros/amazon-ads-mcp-server](https://github.com/MarketplaceAdPros/amazon-ads-mcp-server) ⭐ 14 | 🐛 1 | 🌐 JavaScript | 📅 2025-05-21 📇 ☁️  - Enables tools to interact with Amazon Advertising, analyzing campaign metrics and configurations.
* [stape-io/stape-mcp-server](https://github.com/stape-io/stape-mcp-server) ⭐ 3 | 🐛 3 | 🌐 TypeScript | 📅 2025-10-22 📇 ☁️ – This project implements an MCP (Model Context Protocol) server for the Stape platform. It allows interaction with the Stape API using AI assistants like Claude or AI-powered IDEs like Cursor.

### 📊 <a name="monitoring"></a>Monitoring

Access and analyze application monitoring data. Enables AI models to review error reports and performance metrics.

* [netdata/netdata#Netdata](https://github.com/netdata/netdata/blob/master/src/web/mcp/README.md) ⭐ 76,466 | 🐛 238 | 🌐 C | 📅 2025-10-23 🎖️ 🏠 ☁️ 📟 🍎 🪟 🐧 - Discovery, exploration, reporting and root cause analysis using all observability data, including metrics, logs, systems, containers, processes, and network connections
* [grafana/mcp-grafana](https://github.com/grafana/mcp-grafana) ⭐ 1,740 | 🐛 46 | 🌐 Go | 📅 2025-10-24 🎖️ 🐍 🏠 ☁️ - Search dashboards, investigate incidents and query datasources in your Grafana instance
* [getsentry/sentry-mcp](https://github.com/getsentry/sentry-mcp) ⭐ 398 | 🐛 41 | 🌐 TypeScript | 📅 2025-10-23 🐍 ☁️ - Sentry.io integration for error tracking and performance monitoring
* [pydantic/logfire-mcp](https://github.com/pydantic/logfire-mcp) ⭐ 118 | 🐛 7 | 🌐 Python | 📅 2025-09-24 🎖️ 🐍 ☁️ - Provides access to OpenTelemetry traces and metrics through Logfire
* [mpeirone/zabbix-mcp-server](https://github.com/mpeirone/zabbix-mcp-server) ⭐ 86 | 🐛 3 | 🌐 Python | 📅 2025-10-16 🐍 ☁️ 🐧 🪟 🍎 - Zabbix integration for hosts, items, triggers, templates, problems, data and more.
* [VictoriaMetrics-Community/mcp-victoriametrics](https://github.com/VictoriaMetrics-Community/mcp-victoriametrics) ⭐ 78 | 🐛 2 | 🌐 Go | 📅 2025-10-23 🎖️ 🏎️ 🏠 - Provides comprehensive integration with your [VictoriaMetrics instance APIs](https://docs.victoriametrics.com/victoriametrics/url-examples/) and [documentation](https://docs.victoriametrics.com/) for monitoring, observability, and debugging tasks related to your VictoriaMetrics instances
* [seekrays/mcp-monitor](https://github.com/seekrays/mcp-monitor) ⭐ 73 | 🐛 0 | 🌐 Go | 📅 2025-08-02 🏎️ 🏠 - A system monitoring tool that exposes system metrics via the Model Context Protocol (MCP). This tool allows LLMs to retrieve real-time system information through an MCP-compatible interface.（support CPU、Memory、Disk、Network、Host、Process）
* [hyperb1iss/lucidity-mcp](https://github.com/hyperb1iss/lucidity-mcp) ⭐ 67 | 🐛 6 | 🌐 Python | 📅 2025-03-19 🐍 🏠 - Enhance AI-generated code quality through intelligent, prompt-based analysis across 10 critical dimensions from complexity to security vulnerabilities
* [last9/last9-mcp-server](https://github.com/last9/last9-mcp-server) ⭐ 45 | 🐛 3 | 🌐 Go | 📅 2025-10-20 - Seamlessly bring real-time production context—logs, metrics, and traces—into your local environment to auto-fix code faster
* [metoro-io/metoro-mcp-server](https://github.com/metoro-io/metoro-mcp-server) ⭐ 44 | 🐛 3 | 🌐 Go | 📅 2025-10-09 🎖️ 🏎️ ☁️ - Query and interact with kubernetes environments monitored by Metoro
* [MindscapeHQ/server-raygun](https://github.com/MindscapeHQ/mcp-server-raygun) ⭐ 19 | 🐛 5 | 📅 2025-10-08 📇 ☁️ - Raygun API V3 integration for crash reporting and real user monitoring
* [tumf/grafana-loki-mcp](https://github.com/tumf/grafana-loki-mcp) ⭐ 17 | 🐛 0 | 🌐 Python | 📅 2025-09-05 🐍 🏠 - An MCP server that allows querying Loki logs through the Grafana API.
* [inspektor-gadget/ig-mcp-server](https://github.com/inspektor-gadget/ig-mcp-server) ⭐ 16 | 🐛 7 | 🌐 Go | 📅 2025-10-22 🏎️ ☁️ 🏠 🐧 🪟 🍎 - Debug your Container and Kubernetes workloads with an AI interface powered by eBPF.
* [inventer-dev/mcp-internet-speed-test](https://github.com/inventer-dev/mcp-internet-speed-test) ⭐ 11 | 🐛 0 | 🌐 Python | 📅 2025-10-07 🐍 ☁️ - Internet speed testing with network performance metrics including download/upload speed, latency, jitter analysis, and CDN server detection with geographic mapping
* [edgedelta/edgedelta-mcp-server](https://github.com/edgedelta/edgedelta-mcp-server) ⭐ 5 | 🐛 1 | 🌐 Go | 📅 2025-10-06 🎖️ 🏎️ ☁️ – Interact with Edge Delta anomalies, query logs / patterns / events, and pinpoint root causes and optimize your pipelines.
* [imprvhub/mcp-status-observer](https://github.com/imprvhub/mcp-status-observer) ⭐ 5 | 🐛 0 | 🌐 TypeScript | 📅 2025-09-14 📇 ☁️ -  Model Context Protocol server for monitoring Operational Status of major digital platforms in Claude Desktop.
* [yshngg/pmcp](https://github.com/yshngg/pmcp) ⭐ 3 | 🐛 2 | 🌐 Go | 📅 2025-10-08 🏎️ ☁️ 🏠 🍎 🪟 🐧 - A Prometheus Model Context Protocol Server.

### 🎥 <a name="multimedia-process"></a>Multimedia Process

Provides the ability to handle multimedia, such as audio and video editing, playback, format conversion, also includes video filters, enhancements, and so on

* [sunriseapps/imagesorcery-mcp](https://github.com/sunriseapps/imagesorcery-mcp) ⭐ 223 | 🐛 3 | 🌐 Python | 📅 2025-09-23 🐍 🏠 🐧 🍎 🪟 - ComputerVision-based 🪄 sorcery of image recognition and editing tools for AI assistants.
* [video-creator/ffmpeg-mcp](https://github.com/video-creator/ffmpeg-mcp.git) ⭐ 89 | 🐛 0 | 🌐 Python | 📅 2025-05-13 🎥 🔊 - Using ffmpeg command line to achieve an mcp server, can be very convenient, through the dialogue to achieve the local video search, tailoring, stitching, playback and other functions
* [stass/exif-mcp](https://github.com/stass/exif-mcp) ⭐ 21 | 🐛 1 | 🌐 TypeScript | 📅 2025-05-03 📇 🏠 🐧 🍎 🪟 - A MCP server that allows one to examine image metadata like EXIF, XMP, JFIF and GPS.  This provides foundation for LLM-powered search and analysis of photo librares and image collections.
* [ananddtyagi/gif-creator-mcp](https://github.com/ananddtyagi/gif-creator-mcp/tree/main) ⭐ 9 | 🐛 2 | 🌐 JavaScript | 📅 2025-06-09 📇 🏠 - A MCP server for creating GIFs from your videos.
* [Tommertom/sonos-ts-mcp](https://github.com/Tommertom/sonos-ts-mcp) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2025-10-16 📇 🏠 🍎 🪟 🐧 - Comprehensive Sonos audio system control through pure TypeScript implementation. Features complete device discovery, multi-room playback management, queue control, music library browsing, alarm management, real-time event subscriptions, and audio EQ settings. Includes 50+ tools for seamless smart home audio automation via UPnP/SOAP protocols.
* [bogdan01m/zapcap-mcp-server](https://github.com/bogdan01m/zapcap-mcp-server) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2025-09-11 🐍 ☁️ - MCP server for ZapCap API providing video caption and B-roll generation via natural language

### 🔎 <a name="RAG"></a>end to end RAG platforms

* [vectara/vectara-mcp](https://github.com/vectara/vectara-mcp) ⭐ 23 | 🐛 2 | 🌐 Python | 📅 2025-10-06 🐍 🏠 ☁️ - An MCP server for accessing Vectara's trusted RAG-as-a-service platform.

### 🔎 <a name="search"></a>Search & Data Extraction

* [modelcontextprotocol/server-fetch](https://github.com/modelcontextprotocol/servers/tree/main/src/fetch) ⭐ 71,117 | 🐛 277 | 🌐 TypeScript | 📅 2025-10-24 🐍 🏠 ☁️ - Efficient web content fetching and processing for AI consumption
* [exa-labs/exa-mcp-server](https://github.com/exa-labs/exa-mcp-server) ⭐ 3,106 | 🐛 30 | 🌐 TypeScript | 📅 2025-10-23 🎖️ 📇 ☁️ – A Model Context Protocol (MCP) server lets AI assistants like Claude use the Exa AI Search API for web searches. This setup allows AI models to get real-time web information in a safe and controlled way.
* [devflowinc/trieve](https://github.com/devflowinc/trieve/tree/main/clients/mcp-server) ⭐ 2,533 | 🐛 1 | 🌐 Rust | 📅 2025-10-10 🎖️ 📇 ☁️ 🏠 - Crawl, embed, chunk, search, and retrieve information from datasets through [Trieve](https://trieve.ai)
* [blazickjp/arxiv-mcp-server](https://github.com/blazickjp/arxiv-mcp-server) ⭐ 1,803 | 🐛 27 | 🌐 Python | 📅 2025-08-19 ☁️ 🐍 - Search ArXiv research papers
* [luminati-io/brightdata-mcp](https://github.com/luminati-io/brightdata-mcp) ⭐ 1,501 | 🐛 9 | 🌐 JavaScript | 📅 2025-10-23 📇 ☁️ - Discover, extract, and interact with the web - one interface powering automated access across the public internet.
* [jae-jae/fetcher-mcp](https://github.com/jae-jae/fetcher-mcp) ⭐ 892 | 🐛 6 | 🌐 TypeScript | 📅 2025-10-10 📇 🏠 - MCP server for fetching web page content using Playwright headless browser, supporting Javascript rendering and intelligent content extraction, and outputting Markdown or HTML format.
* [nickclyde/duckduckgo-mcp-server](https://github.com/nickclyde/duckduckgo-mcp-server) ⭐ 569 | 🐛 18 | 🌐 Python | 📅 2025-03-11 🐍 ☁️ - Web search using DuckDuckGo
* [Aas-ee/open-webSearch](https://github.com/Aas-ee/open-webSearch) ⭐ 407 | 🐛 7 | 🌐 TypeScript | 📅 2025-08-31 🐍 📇 ☁️ - Web search using free multi-engine search (NO API KEYS REQUIRED) — Supports Bing, Baidu, DuckDuckGo, Brave, Exa, and CSDN.
* [genomoncology/biomcp](https://github.com/genomoncology/biomcp) ⭐ 327 | 🐛 1 | 🌐 Python | 📅 2025-10-23 🐍 ☁️ - Biomedical research server providing access to PubMed, ClinicalTrials.gov, and MyVariant.info.
* [brave/brave-search-mcp-server](https://github.com/brave/brave-search-mcp-server) ⭐ 297 | 🐛 10 | 🌐 TypeScript | 📅 2025-10-23 📇 ☁️ - Web search capabilities using Brave's Search API
* [Ihor-Sokoliuk/MCP-SearXNG](https://github.com/ihor-sokoliuk/mcp-searxng) ⭐ 295 | 🐛 9 | 🌐 TypeScript | 📅 2025-10-19 📇 🏠/☁️ - A Model Context Protocol Server for [SearXNG](https://docs.searxng.org)
* [mzxrai/mcp-webresearch](https://github.com/mzxrai/mcp-webresearch) ⚠️ Archived 🔍 📚 - Search Google and do deep web research on any topic
* [jae-jae/g-search-mcp](https://github.com/jae-jae/g-search-mcp) ⭐ 212 | 🐛 5 | 🌐 TypeScript | 📅 2025-06-14 📇 🏠 - A powerful MCP server for Google search that enables parallel searching with multiple keywords simultaneously.
* [kagisearch/kagimcp](https://github.com/kagisearch/kagimcp) ⭐ 208 | 🐛 5 | 🌐 Python | 📅 2025-07-28 ☁️ 📇 – Official Kagi Search MCP Server
* [apify/mcp-server-rag-web-browser](https://github.com/apify/mcp-server-rag-web-browser) ⭐ 188 | 🐛 0 | 🌐 JavaScript | 📅 2025-08-21 📇 ☁️ - An MCP server for Apify's open-source RAG Web Browser Actor to perform web searches, scrape URLs, and return content in Markdown.
* [reading-plus-ai/mcp-server-deep-research](https://github.com/reading-plus-ai/mcp-server-deep-research) ⭐ 182 | 🐛 3 | 🌐 Python | 📅 2025-03-25 📇 ☁️ - MCP server providing OpenAI/Perplexity-like autonomous deep research, structured query elaboration, and concise reporting.
* [hellokaton/unsplash-mcp-server](https://github.com/hellokaton/unsplash-mcp-server) ⭐ 179 | 🐛 3 | 🌐 Python | 📅 2025-07-07) 🐍 ☁️ - A MCP server for Unsplash image search.
* [andybrandt/mcp-simple-arxiv](https://github.com/andybrandt/mcp-simple-arxiv) ⭐ 161 | 🐛 1 | 🌐 Python | 📅 2025-09-07 - 🐍 ☁️  MCP for LLM to search and read papers from arXiv
* [fatwang2/search1api-mcp](https://github.com/fatwang2/search1api-mcp) ⭐ 156 | 🐛 7 | 🌐 TypeScript | 📅 2025-04-06 📇 ☁️ - Search via search1api (requires paid API key)
* [andybrandt/mcp-simple-pubmed](https://github.com/andybrandt/mcp-simple-pubmed) ⭐ 137 | 🐛 3 | 🌐 Python | 📅 2025-09-24 - 🐍 ☁️  MCP to search and read medical / life sciences papers from PubMed.
* [deadletterq/mcp-opennutrition](https://github.com/deadletterq/mcp-opennutrition) ⭐ 122 | 🐛 1 | 🌐 TypeScript | 📅 2025-06-11 📇 🏠 - Local MCP server for searching 300,000+ foods, nutrition facts, and barcodes from the OpenNutrition database.
* [tinyfish-io/agentql-mcp](https://github.com/tinyfish-io/agentql-mcp) ⭐ 116 | 🐛 3 | 🌐 JavaScript | 📅 2025-10-22 🎖️ 📇 ☁️ - MCP server that provides [AgentQL](https://agentql.com)'s data extraction capabilities.
* [SecretiveShell/MCP-searxng](https://github.com/SecretiveShell/MCP-searxng) ⭐ 106 | 🐛 1 | 🌐 Python | 📅 2025-02-21 🐍 🏠 - An MCP Server to connect to searXNG instances
* [just-every/mcp-read-website-fast](https://github.com/just-every/mcp-read-website-fast) ⭐ 101 | 🐛 2 | 🌐 JavaScript | 📅 2025-08-29 📇 🏠 - Fast, token-efficient web content extraction for AI agents - converts websites to clean Markdown while preserving links. Features Mozilla Readability, smart caching, polite crawling with robots.txt support, and concurrent fetching.
* [vectorize-io/vectorize-mcp-server](https://github.com/vectorize-io/vectorize-mcp-server/) ⭐ 96 | 🐛 3 | 🌐 JavaScript | 📅 2025-06-12 ☁️ 📇 - [Vectorize](https://vectorize.io) MCP server for advanced retrieval, Private Deep Research, Anything-to-Markdown file extraction and text chunking.
* [chanmeng/google-news-mcp-server](https://github.com/ChanMeng666/server-google-news) ⭐ 89 | 🐛 2 | 🌐 TypeScript | 📅 2025-09-12 📇 ☁️ - Google News integration with automatic topic categorization, multi-language support, and comprehensive search capabilities including headlines, stories, and related topics through [SerpAPI](https://serpapi.com/).
* [just-every/mcp-screenshot-website-fast](https://github.com/just-every/mcp-screenshot-website-fast) ⭐ 86 | 🐛 1 | 🌐 JavaScript | 📅 2025-07-21 📇 🏠 - Fast screenshot capture tool optimized for Claude Vision API. Automatically tiles full pages into 1072x1072 chunks for optimal AI processing with configurable viewports and wait strategies for dynamic content.
* [mikechao/brave-search-mcp](https://github.com/mikechao/brave-search-mcp) ⭐ 84 | 🐛 0 | 🌐 TypeScript | 📅 2025-07-29 📇 ☁️ - Web, Image, News, Video, and Local Point of Interest search capabilities using Brave's Search API
* [nkapila6/mcp-local-rag](https://github.com/nkapila6/mcp-local-rag) ⭐ 84 | 🐛 4 | 🌐 Python | 📅 2025-10-20 🏠 🐍 - "primitive" RAG-like web search model context protocol (MCP) server that runs locally. No APIs needed.
* [lfnovo/content-core](https://github.com/lfnovo/content-core) ⭐ 71 | 🐛 4 | 🌐 Jupyter Notebook | 📅 2025-10-21 🐍 🏠 - Extract content from URLs, documents, videos, and audio files using intelligent auto-engine selection. Supports web pages, PDFs, Word docs, YouTube transcripts, and more with structured JSON responses.
* [takashiishida/arxiv-latex-mcp](https://github.com/takashiishida/arxiv-latex-mcp) ⭐ 70 | 🐛 3 | 🌐 Python | 📅 2025-08-15 🐍 ☁️ - Get the LaTeX source of arXiv papers to handle mathematical content and equations
* [ConechoAI/openai-websearch-mcp](https://github.com/ConechoAI/openai-websearch-mcp/) ⭐ 69 | 🐛 5 | 🌐 Python | 📅 2025-09-12 🐍 🏠 ☁️ - This is a Python-based MCP server that provides OpenAI `web_search` build-in tool.
* [OctagonAI/octagon-deep-research-mcp](https://github.com/OctagonAI/octagon-deep-research-mcp) ⭐ 67 | 🐛 1 | 🌐 JavaScript | 📅 2025-06-03 🎖️ 📇 ☁️ 🏠 - Lightning-Fast, High-Accuracy Deep Research Agent
* [zhsama/duckduckgo-mcp-server](https://github.com/zhsama/duckduckgo-mpc-server/) ⭐ 63 | 🐛 1 | 🌐 TypeScript | 📅 2025-04-04 📇 🏠 ☁️ - This is a TypeScript-based MCP server that provides DuckDuckGo search functionality.
* [leehanchung/bing-search-mcp](https://github.com/leehanchung/bing-search-mcp) ⭐ 61 | 🐛 3 | 🌐 Python | 📅 2025-04-04 📇 ☁️ - Web search capabilities using Microsoft Bing Search API
* [scrapeless-ai/scrapeless-mcp-server](https://github.com/scrapeless-ai/scrapeless-mcp-server) ⭐ 56 | 🐛 0 | 🌐 TypeScript | 📅 2025-09-23 🐍 ☁️ - The Scrapeless Model Context Protocol service acts as an MCP server connector to the Google SERP API, enabling web search within the MCP ecosystem without leaving it.
* [erithwik/mcp-hn](https://github.com/erithwik/mcp-hn) ⭐ 53 | 🐛 3 | 🌐 Python | 📅 2025-07-14 🐍 ☁️ - An MCP server to search Hacker News, get top stories, and more.
* [0xdaef0f/job-searchoor](https://github.com/0xDAEF0F/job-searchoor) ⭐ 50 | 🐛 3 | 🌐 JavaScript | 📅 2025-04-08 📇 🏠 - An MCP server for searching job listings with filters for date, keywords, remote work options, and more.
* [zoomeye-ai/mcp\_zoomeye](https://github.com/zoomeye-ai/mcp_zoomeye) ⭐ 48 | 🐛 1 | 🌐 Python | 📅 2025-06-27 📇 ☁️ - Querying network asset information by ZoomEye MCP Server
* [ricocf/mcp-wolframalpha](https://github.com/ricocf/mcp-wolframalpha) ⭐ 47 | 🐛 2 | 🌐 Python | 📅 2025-08-06 🐍 🏠 ☁️ - An MCP server lets AI assistants use the Wolfram Alpha API for real-time access to computational knowledge and data.
* [Tomatio13/mcp-server-tavily](https://github.com/Tomatio13/mcp-server-tavily) ⭐ 44 | 🐛 1 | 🌐 Python | 📅 2025-08-19 ☁️ 🐍 – Tavily AI search API
* [isnow890/naver-search-mcp](https://github.com/isnow890/naver-search-mcp) ⭐ 43 | 🐛 0 | 🌐 JavaScript | 📅 2025-10-19 📇 ☁️ - MCP server for Naver Search API integration, supporting blog, news, shopping search and DataLab analytics features.
* [ac3xx/mcp-servers-kagi](https://github.com/ac3xx/mcp-servers-kagi) ⭐ 39 | 🐛 6 | 🌐 TypeScript | 📅 2024-12-13 📇 ☁️ - Kagi search API integration
* [ananddtyagi/webpage-screenshot-mcp](https://github.com/ananddtyagi/webpage-screenshot-mcp) ⭐ 39 | 🐛 4 | 🌐 JavaScript | 📅 2025-06-29 📇 🏠 - A MCP server for taking screenshots of webpages to use as feedback during UI developement.
* [yamanoku/baseline-mcp-server](https://github.com/yamanoku/baseline-mcp-server) ⭐ 36 | 🐛 4 | 🌐 TypeScript | 📅 2025-08-25 📇 🏠 - MCP server that searches Baseline status using Web Platform API
* [DappierAI/dappier-mcp](https://github.com/DappierAI/dappier-mcp) ⭐ 34 | 🐛 1 | 🌐 Python | 📅 2025-06-27 🐍 ☁️ - Enable fast, free real-time web search and access premium data from trusted media brands—news, financial markets, sports, entertainment, weather, and more. Build powerful AI agents with Dappier.
* [webscraping-ai/webscraping-ai-mcp-server](https://github.com/webscraping-ai/webscraping-ai-mcp-server) ⭐ 31 | 🐛 3 | 🌐 JavaScript | 📅 2025-04-17 🎖️ 📇 ☁️ - Interact with [WebScraping.ai](https://webscraping.ai) for web data extraction and scraping.
* [Dumpling-AI/mcp-server-dumplingai](https://github.com/Dumpling-AI/mcp-server-dumplingai) ⭐ 28 | 🐛 7 | 🌐 JavaScript | 📅 2025-07-10 🎖️ 📇 ☁️ - Access data, web scraping, and document conversion APIs by [Dumpling AI](https://www.dumplingai.com/)
* [pragmar/mcp-server-webcrawl](https://github.com/pragmar/mcp-server-webcrawl) ⭐ 26 | 🐛 0 | 🌐 HTML | 📅 2025-09-24 🐍 🏠 - Advanced search and retrieval for web crawler data. Supports WARC, wget, Katana, SiteOne, and InterroBot crawlers.
* [format37/youtube\_mcp](https://github.com/format37/youtube_mcp) ⭐ 24 | 🐛 2 | 🌐 Python | 📅 2025-07-21 🐍 ☁️ – MCP server that transcribes YouTube videos to text. Uses yt-dlp to download audio and OpenAI's Whisper-1 for more precise transcription than youtube captions. Provide a YouTube URL and get back the full transcript splitted by chunks for long videos.
* [imprvhub/mcp-domain-availability](https://github.com/imprvhub/mcp-domain-availability) ⭐ 20 | 🐛 1 | 🌐 Python | 📅 2025-07-03 🐍 ☁️ - A Model Context Protocol (MCP) server that enables Claude Desktop to check domain availability across 50+ TLDs. Features DNS/WHOIS verification, bulk checking, and smart suggestions. Zero-clone installation via uvx.
* [Linked-API/linkedapi-mcp](https://github.com/Linked-API/linkedapi-mcp) ⭐ 18 | 🐛 1 | 🌐 TypeScript | 📅 2025-09-29 🎖️ 📇 ☁️ - MCP server that lets AI assistants control LinkedIn accounts and retrieve real-time data.
* [the0807/GeekNews-MCP-Server](https://github.com/the0807/GeekNews-MCP-Server) ⭐ 16 | 🐛 2 | 🌐 Python | 📅 2025-04-13 🐍 ☁️ - An MCP Server that retrieves and processes news data from the GeekNews site.
* [adawalli/nexus](https://github.com/adawalli/nexus) ⭐ 15 | 🐛 2 | 🌐 TypeScript | 📅 2025-10-21 📇 ☁️ - AI-powered web search server using Perplexity Sonar models with source citations. Zero-install setup via NPX.
* [angheljf/nyt](https://github.com/angheljf/nyt) ⭐ 15 | 🐛 2 | 🌐 JavaScript | 📅 2025-01-27 📇 ☁️ - Search articles using the NYTimes API
* [r-huijts/opentk-mcp](https://github.com/r-huijts/opentk-mcp) ⭐ 15 | 🐛 0 | 🌐 HTML | 📅 2025-10-21 📇 ☁️ - Access Dutch Parliament (Tweede Kamer) information including documents, debates, activities, and legislative cases through structured search capabilities (based on opentk project by Bert Hubert)
* [hbg/mcp-paperswithcode](https://github.com/hbg/mcp-paperswithcode) ⭐ 14 | 🐛 3 | 🌐 Python | 📅 2025-06-07 - 🐍 ☁️ MCP to search through PapersWithCode API
* [kehvinbehvin/json-mcp-filter](https://github.com/kehvinbehvin/json-mcp-filter) ⭐ 14 | 🐛 1 | 🌐 JavaScript | 📅 2025-10-23 ️🏠 📇 – Stop bloating your LLM context. Query & Extract only what you need from your JSON files.
* [joelio/stocky](https://github.com/joelio/stocky) ⭐ 12 | 🐛 1 | 🌐 Python | 📅 2025-10-13 🐍 ☁️ 🏠 - An MCP server for searching and downloading royalty-free stock photography from Pexels and Unsplash. Features multi-provider search, rich metadata, pagination support, and async performance for AI assistants to find and access high-quality images.
* [imprvhub/mcp-rss-aggregator](https://github.com/imprvhub/mcp-rss-aggregator) ⭐ 12 | 🐛 0 | 🌐 TypeScript | 📅 2025-09-14 📇 ☁️ 🏠 - Model Context Protocol Server for aggregating RSS feeds in Claude Desktop.
* [Himalayas-App/himalayas-mcp](https://github.com/Himalayas-App/himalayas-mcp) ⭐ 10 | 🐛 1 | 📅 2025-06-06 📇 ☁️ - Access tens of thousands of remote job listings and company information. This public MCP server provides real-time access to Himalayas' remote jobs database.
* [serkan-ozal/driflyte-mcp-server](https://github.com/serkan-ozal/driflyte-mcp-server) ⭐ 8 | 🐛 2 | 🌐 TypeScript | 📅 2025-10-02 🎖️ 📇 ☁️ 🏠 - The Driflyte MCP Server exposes tools that allow AI assistants to query and retrieve topic-specific knowledge from recursively crawled and indexed web pages.
* [emicklei/melrose-mcp](https://github.com/emicklei/melrose-mcp) ⭐ 7 | 🐛 1 | 🌐 Go | 📅 2025-08-01 🏎️ 🏠 - Plays [Melrōse](https://melrōse.org) music expressions as MIDI
* [tianqitang1/enrichr-mcp-server](https://github.com/tianqitang1/enrichr-mcp-server) ⭐ 7 | 🐛 3 | 🌐 JavaScript | 📅 2025-06-29 📇 ☁️ - A MCP server that provides gene set enrichment analysis using the Enrichr API
* [imprvhub/mcp-claude-hackernews](https://github.com/imprvhub/mcp-claude-hackernews) ⭐ 7 | 🐛 2 | 🌐 TypeScript | 📅 2025-09-15 📇 🏠 ☁️ - An integration that allows Claude Desktop to interact with Hacker News using the Model Context Protocol (MCP).
* [kshern/mcp-tavily](https://github.com/kshern/mcp-tavily.git) ⭐ 6 | 🐛 0 | 🌐 JavaScript | 📅 2025-02-24 ☁️ 📇 – Tavily AI search API
* [searchcraft-inc/searchcraft-mcp-server](https://github.com/searchcraft-inc/searchcraft-mcp-server) ⭐ 6 | 🐛 4 | 🌐 TypeScript | 📅 2025-10-18 🎖️ 📇 ☁️ - Official MCP server for managing Searchcraft clusters, creating a search index, generating an index dynamically given a data file and for easily importing data into a search index given a feed or local json file.
* [vitorpavinato/ncbi-mcp-server](https://github.com/vitorpavinato/ncbi-mcp-server) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2025-06-28 🐍 ☁️ 🏠 - Comprehensive NCBI/PubMed literature search server with advanced analytics, caching, MeSH integration, related articles discovery, and batch processing for all life sciences and biomedical research.
* [Bigsy/Clojars-MCP-Server](https://github.com/Bigsy/Clojars-MCP-Server) ⭐ 5 | 🐛 2 | 🌐 JavaScript | 📅 2025-06-25 📇 ☁️ - Clojars MCP Server for upto date dependency information of Clojure libraries
* [Pearch-ai/mcp\_pearch](https://github.com/Pearch-ai/mcp_pearch) ⭐ 5 | 🐛 1 | 🌐 Python | 📅 2025-07-03 🎖️ 🐍 ☁️ - Best people search engine that reduces the time spent on talent discovery
* [cameronrye/gopher-mcp](https://github.com/cameronrye/gopher-mcp) ⭐ 4 | 🐛 7 | 🌐 Python | 📅 2025-09-22 🐍 🏠 - Modern, cross-platform MCP server enabling AI assistants to browse and interact with both Gopher protocol and Gemini protocol resources safely and efficiently. Features dual protocol support, TLS security, and structured content extraction.
* [nyxn-ai/NyxDocs](https://github.com/nyxn-ai/NyxDocs) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2025-06-24 🐍 ☁️ 🏠 - Specialized MCP server for cryptocurrency project documentation management with multi-blockchain support (Ethereum, BSC, Polygon, Solana).
* [shopsavvy/shopsavvy-mcp-server](https://github.com/shopsavvy/shopsavvy-mcp-server) ⭐ 3 | 🐛 1 | 🌐 JavaScript | 📅 2025-07-30 🎖️ 📇 ☁️ - Complete product and pricing data solution for AI assistants. Search for products by barcode/ASIN/URL, access detailed product metadata, access comprehensive pricing data from thousands of retailers, view and track price history, and more.
* [kimdonghwi94/Web-Analyzer-MCP](https://github.com/kimdonghwi94/web-analyzer-mcp) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2025-09-03 🐍 🏠 🍎 🪟 🐧 - Extracts clean web content for RAG and provides Q\&A about web pages.
* [parallel-web/search-mcp](https://github.com/parallel-web/search-mcp) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2025-10-10 ☁️ 🔎 - Highest Accuracy Web Search for AI
* [parallel-web/task-mcp](https://github.com/parallel-web/task-mcp) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2025-10-10 ☁️ 🔎 - Highest Accuracy Deep Research and Batch Tasks MCP
* [QuentinCody/catalysishub-mcp-server](https://github.com/QuentinCody/catalysishub-mcp-server) ⭐ 1 | 🐛 2 | 🌐 Python | 📅 2025-05-20 🐍 - Unofficial MCP server for searching and retrieving scientific data from the Catalysis Hub database, providing access to computational catalysis research and surface reaction data.
* [urlbox/urlbox-mcp-server](https://github.com/urlbox/urlbox-mcp-server/) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2025-10-17 - 📇 🏠 A reliable MCP server for generating and managing screenshots, PDFs, and videos, performing AI-powered screenshot analysis, and extracting web content (Markdown, metadata, and HTML) via the [Urlbox](https://urlbox.com) API.
* [dealx/mcp-server](https://github.com/DealExpress/mcp-server) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2025-04-01 ☁️ - MCP Server for DealX platform
* [sascharo/gxtract](https://github.com/sascharo/gxtract) ⭐ 0 | 🐛 1 | 🌐 Python | 📅 2025-05-20 🐍 ☁️ 🪟 🐧 🍎 - GXtract is a MCP server designed to integrate with VS Code and other compatible editors (documentation: [sascharo.github.io/gxtract](https://sascharo.github.io/gxtract)). It provides a suite of tools for interacting with the GroundX platform, enabling you to leverage its powerful document understanding capabilities directly within your development environment.

### 🔒 <a name="security"></a>Security

* [LaurieWired/GhidraMCP](https://github.com/LaurieWired/GhidraMCP) ⭐ 6,327 | 🐛 44 | 🌐 Java | 📅 2025-06-23 ☕ 🏠 - A Model Context Protocol server for Ghidra that enables LLMs to autonomously reverse engineer applications. Provides tools for decompiling binaries, renaming methods and data, and listing methods, classes, imports, and exports.
* [mrexodia/ida-pro-mcp](https://github.com/mrexodia/ida-pro-mcp) ⭐ 3,993 | 🐛 19 | 🌐 Python | 📅 2025-10-10 🐍 🏠 - MCP server for IDA Pro, allowing you to perform binary analysis with AI assistants. This plugin implement decompilation, disassembly and allows you to generate malware analysis reports automatically.
* [mariocandela/beelzebub](https://github.com/mariocandela/beelzebub) ⭐ 1,618 | 🐛 6 | 🌐 Go | 📅 2025-10-22 ☁️ - Beelzebub is a honeypot framework that lets you build honeypot tools using MCP. Its purpose is to detect prompt injection or malicious agent behavior. The underlying idea is to provide the agent with tools it would never use in its normal work.
* [safedep/vet](https://github.com/safedep/vet/blob/main/docs/mcp.md) ⭐ 820 | 🐛 91 | 🌐 Go | 📅 2025-10-17 🎖️ 🏎️ ☁️ 🍎 🪟 🐧 - vet-mcp checks open source packages—like those suggested by AI coding tools—for vulnerabilities and malicious code. It supports npm and PyPI, and runs locally via Docker or as a standalone binary for fast, automated vetting.
* [semgrep/mcp](https://github.com/semgrep/mcp) ⚠️ Archived 📇 ☁️ Allow AI agents to scan code for security vulnerabilites using [Semgrep](https://semgrep.dev).
* [zinja-coder/jadx-ai-mcp](https://github.com/zinja-coder/jadx-ai-mcp) ⭐ 593 | 🐛 4 | 🌐 Java | 📅 2025-10-22 ☕ 🏠 - JADX-AI-MCP is a plugin and MCP Server for the JADX decompiler that integrates directly with Model Context Protocol (MCP) to provide live reverse engineering support with LLMs like Claude.
* [jtang613/GhidrAssistMCP](https://github.com/jtang613/GhidrAssistMCP) ⭐ 326 | 🐛 0 | 🌐 Java | 📅 2025-10-21 ☕ 🏠 - A native Model Context Protocol server for Ghidra. Includes GUI configuration and logging, 31 powerful tools and no external dependencies.
* [zinja-coder/apktool-mcp-server](https://github.com/zinja-coder/apktool-mcp-server) ⭐ 236 | 🐛 0 | 🌐 Python | 📅 2025-09-12 🐍 🏠 - APKTool MCP Server is a MCP server for the Apk Tool to provide automation in reverse engineering of Android APKs.
* [BurtTheCoder/mcp-maigret](https://github.com/BurtTheCoder/mcp-maigret) ⭐ 197 | 🐛 5 | 🌐 JavaScript | 📅 2025-03-03 📇 🪟 ☁️ - MCP server for maigret, a powerful OSINT tool that collects user account information from various public sources. This server provides tools for searching usernames across social networks and analyzing URLs.
* [securityfortech/secops-mcp](https://github.com/securityfortech/secops-mcp) ⭐ 156 | 🐛 3 | 🌐 Python | 📅 2025-09-17 🐍 🏠 - All-in-one security testing toolbox that brings together popular open source tools through a single MCP interface. Connected to an AI agent, it enables tasks like pentesting, bug bounty hunting, threat hunting, and more.
* [gbrigandi/mcp-server-wazuh](https://github.com/gbrigandi/mcp-server-wazuh) ⭐ 130 | 🐛 4 | 🌐 Rust | 📅 2025-07-10 🦀 🏠 🚨 🍎 🪟 🐧 - A Rust-based MCP server bridging Wazuh SIEM with AI assistants, providing real-time security alerts and event data for enhanced contextual understanding.
* [fosdickio/binary\_ninja\_mcp](https://github.com/fosdickio/binary_ninja_mcp) ⭐ 106 | 🐛 8 | 🌐 Python | 📅 2025-09-24 🐍 🏠 🍎 🪟 🐧 - A Binary Ninja plugin, MCP server, and bridge that seamlessly integrates [Binary Ninja](https://binary.ninja) with your favorite MCP client.  It enables you to automate the process of performing binary analysis and reverse engineering.
* [BurtTheCoder/mcp-virustotal](https://github.com/BurtTheCoder/mcp-virustotal) ⭐ 84 | 🐛 4 | 🌐 TypeScript | 📅 2025-03-03 📇 🪟 ☁️ - MCP server for querying the VirusTotal API. This server provides tools for scanning URLs, analyzing file hashes, and retrieving IP address reports.
* [BurtTheCoder/mcp-shodan](https://github.com/BurtTheCoder/mcp-shodan) ⭐ 78 | 🐛 4 | 🌐 JavaScript | 📅 2025-03-03 📇 🪟 ☁️ - MCP server for querying the Shodan API and Shodan CVEDB. This server provides tools for IP lookups, device searches, DNS lookups, vulnerability queries, CPE lookups, and more.
* [13bm/GhidraMCP](https://github.com/13bm/GhidraMCP) ⭐ 72 | 🐛 1 | 🌐 Java | 📅 2025-03-26 🐍 ☕ 🏠 - MCP server for integrating Ghidra with AI assistants. This plugin enables binary analysis, providing tools for function inspection, decompilation, memory exploration, and import/export analysis via the Model Context Protocol.
* [roadwy/cve-search\_mcp](https://github.com/roadwy/cve-search_mcp) ⭐ 60 | 🐛 2 | 🌐 Python | 📅 2025-07-26 🐍 🏠 - A Model Context Protocol (MCP) server for querying the CVE-Search API. This server provides comprehensive access to CVE-Search, browse vendor and product、get CVE per CVE-ID、get the last updated CVEs.
* [mobb-dev/mobb-vibe-shield-mcp](https://github.com/mobb-dev/bugsy?tab=readme-ov-file#model-context-protocol-mcp-server) ⭐ 59 | 🐛 1 | 🌐 TypeScript | 📅 2025-10-22 🎖️ 📇 ☁️ 🍎 🪟 🐧 - [Mobb Vibe Shield](https://vibe.mobb.ai/) identifies and remediates vulnerabilities in both human and AI-written code, ensuring your applications remain secure without slowing development.
* [atomicchonk/roadrecon\_mcp\_server](https://github.com/atomicchonk/roadrecon_mcp_server) ⭐ 48 | 🐛 1 | 🌐 Python | 📅 2025-03-30 🐍 🪟 🏠 MCP server for analyzing ROADrecon gather results from Azure tenant enumeration
* [qianniuspace/mcp-security-audit](https://github.com/qianniuspace/mcp-security-audit) ⭐ 44 | 🐛 0 | 🌐 TypeScript | 📅 2025-07-18 📇 ☁️ A powerful MCP (Model Context Protocol) Server that audits npm package dependencies for security vulnerabilities. Built with remote npm registry integration for real-time security checks.
* [fr0gger/MCP\_Security](https://github.com/fr0gger/MCP_Security) ⭐ 43 | 🐛 1 | 🌐 Python | 📅 2025-01-22 📇 ☁️ - MCP server for querying the ORKL API. This server provides tools for fetching threat reports, analyzing threat actors, and retrieving intelligence sources.
* [BurtTheCoder/mcp-dnstwist](https://github.com/BurtTheCoder/mcp-dnstwist) ⭐ 37 | 🐛 6 | 🌐 JavaScript | 📅 2025-03-03 📇 🪟 ☁️ - MCP server for dnstwist, a powerful DNS fuzzing tool that helps detect typosquatting, phishing, and corporate espionage.
* [Gaffx/volatility-mcp](https://github.com/Gaffx/volatility-mcp) ⭐ 34 | 🐛 2 | 🌐 Python | 📅 2025-07-09 - MCP server for Volatility 3.x, allowing you to perform memory forensics analysis with AI assistant. Experience memory forensics without barriers as plugins like pslist and netscan become accessible through clean REST APIs and LLMs.
* [panther-labs/mcp-panther](https://github.com/panther-labs/mcp-panther) ⭐ 32 | 🐛 10 | 🌐 Python | 📅 2025-10-22 🎖️ 🐍 ☁️ 🍎 - MCP server that enables security professionals to interact with Panther's SIEM platform using natural language for writing detections, querying logs, and managing alerts.
* [slouchd/cyberchef-api-mcp-server](https://github.com/slouchd/cyberchef-api-mcp-server) ⭐ 27 | 🐛 1 | 🌐 Python | 📅 2025-04-17 🐍 ☁️ - MCP server for interacting with the CyberChef server API which will allow an MCP client to utilise the CyberChef operations.
* [hieutran/entraid-mcp-server](https://github.com/hieuttmmo/entraid-mcp-server) ⭐ 26 | 🐛 2 | 🌐 Python | 📅 2025-05-02 🐍 ☁️ - A MCP server for Microsoft Entra ID (Azure AD) directory, user, group, device, sign-in, and security operations via Microsoft Graph Python SDK.
* [StacklokLabs/osv-mcp](https://github.com/StacklokLabs/osv-mcp) ⭐ 25 | 🐛 1 | 🌐 Go | 📅 2025-10-22 🏎️ ☁️ - Access the OSV (Open Source Vulnerabilities) database for vulnerability information. Query vulnerabilities by package version or commit, batch query multiple packages, and get detailed vulnerability information by ID.
* [firstorderai/authenticator\_mcp](https://github.com/firstorderai/authenticator_mcp) ⭐ 24 | 🐛 0 | 🌐 TypeScript | 📅 2025-08-19 📇 🏠 🍎 🪟 🐧 – A secure MCP (Model Context Protocol) server that enables AI agents to interact with the Authenticator App.
* [vespo92/OPNSenseMCP](https://github.com/vespo92/OPNSenseMCP) ⭐ 24 | 🐛 0 | 🌐 TypeScript | 📅 2025-08-24 📇 🏠 - MCP Server for managing & interacting with Open Source NGFW OPNSense via Natural Language
* [intruder-io/intruder-mcp](https://github.com/intruder-io/intruder-mcp) ⭐ 21 | 🐛 1 | 🌐 Python | 📅 2025-06-12 🐍 ☁️ - MCP server to access [Intruder](https://www.intruder.io/), helping you identify, understand, and fix security vulnerabilities in your infrastructure.
* [nickpending/mcp-recon](https://github.com/nickpending/mcp-recon) ⭐ 20 | 🐛 0 | 🌐 Go | 📅 2025-04-22 🏎️ 🏠 - Conversational recon interface and MCP server powered by httpx and asnmap. Supports various reconnaissance levels for domain analysis, security header inspection, certificate analysis, and ASN lookup.
* [co-browser/attestable-mcp-server](https://github.com/co-browser/attestable-mcp-server) ⭐ 17 | 🐛 3 | 🌐 Python | 📅 2025-03-28 🐍 🏠 ☁️ 🐧 - An MCP server running inside a trusted execution environment (TEE) via Gramine, showcasing remote attestation using [RA-TLS](https://gramine.readthedocs.io/en/stable/attestation.html). This allows an MCP client to verify the server before conencting.
* [gbrigandi/mcp-server-cortex](https://github.com/gbrigandi/mcp-server-cortex) ⭐ 12 | 🐛 1 | 🌐 Rust | 📅 2025-07-18 🦀 🏠 🚨 🍎 🪟 🐧 - A Rust-based MCP server to integrate Cortex, enabling observable analysis and automated security responses through AI.
* [pullkitsan/mobsf-mcp-server](https://github.com/pullkitsan/mobsf-mcp-server) ⭐ 12 | 🐛 1 | 🌐 TypeScript | 📅 2025-07-19 🦀 🏠 🍎 🪟 🐧 - A MCP server for MobSF which can be used for static and dynamic analysis of Android and iOS application.
* [AIM-Intelligence/AIM-Guard-MCP](https://github.com/AIM-Intelligence/AIM-MCP) ⭐ 11 | 🐛 0 | 🌐 TypeScript | 📅 2025-10-13 📇 🏠 🍎 🪟 🐧 - Security-focused MCP server that provides safety guidelines and content analysis for AI agents.
* [gbrigandi/mcp-server-thehive](https://github.com/gbrigandi/mcp-server-thehive) ⭐ 11 | 🐛 1 | 🌐 Rust | 📅 2025-05-27 🦀 🏠 🚨 🍎 🪟 🐧 - A Rust-based MCP server to integrate TheHive, facilitating collaborative security incident response and case management via AI.
* [jyjune/mcp\_vms](https://github.com/jyjune/mcp_vms) ⭐ 11 | 🐛 1 | 🌐 Python | 📅 2025-08-23 🐍 🏠 🪟 - A Model Context Protocol (MCP) server designed to connect to a CCTV recording program (VMS) to retrieve recorded and live video streams. It also provides tools to control the VMS software, such as showing live or playback dialogs for specific channels at specified times.
* [sanyambassi/ciphertrust-manager-mcp-server](https://github.com/sanyambassi/ciphertrust-manager-mcp-server) ⭐ 7 | 🐛 0 | 🌐 Python | 📅 2025-08-20 🐍 ☁️ 🏠 🐧 🪟 - MCP server for Thales CipherTrust Manager integration, enabling secure key management, cryptographic operations, and compliance monitoring through AI assistants.
* [rad-security/mcp-server](https://github.com/rad-security/mcp-server) ⭐ 4 | 🐛 0 | 🌐 TypeScript | 📅 2025-10-23 📇 ☁️ - MCP server for RAD Security, providing AI-powered security insights for Kubernetes and cloud environments. This server provides tools for querying the Rad Security API and retrieving security findings, reports, runtime data and many more.
* [HaroldFinchIFT/vuln-nist-mcp-server](https://github.com/HaroldFinchIFT/vuln-nist-mcp-server) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2025-09-23 🐍 ☁️️ 🍎 🪟 🐧 - A Model Context Protocol (MCP) server for querying NIST National Vulnerability Database (NVD) API endpoints.
* [sanyambassi/thales-cdsp-cakm-mcp-server](https://github.com/sanyambassi/thales-cdsp-cakm-mcp-server) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2025-09-04 🐍 ☁️ 🏠 🐧 🪟 - MCP server for Thales CDSP CAKM integration, enabling secure key management, cryptographic operations, and compliance monitoring through AI assistants for Ms SQL and Oracle Databases.
* [sanyambassi/thales-cdsp-crdp-mcp-server](https://github.com/sanyambassi/thales-cdsp-crdp-mcp-server) ⭐ 2 | 🐛 0 | 🌐 JavaScript | 📅 2025-09-04 📇 ☁️ 🏠 🐧 🪟 - MCP server for Thales CipherTrust Manager RestFul Data Protection service.
* [adeptus-innovatio/solvitor-mcp](https://github.com/Adeptus-Innovatio/solvitor-mcp) ⭐ 2 | 🐛 0 | 🌐 Rust | 📅 2025-10-02 🦀 🏠 - Solvitor MCP server provides tools to access reverse engineering tools that help developers extract IDL files from closed-source Solana smart contracts and decompile them.
* [dkvdm/onepassword-mcp-server](https://github.com/dkvdm/onepassword-mcp-server) - An MCP server that enables secure credential retrieval from 1Password to be used by Agentic AI.

### 🌐 <a name="social-media"></a>Social Media

Integration with social media platforms to allow posting, analytics, and interaction management. Enables AI-driven automation for social presence.

* [karanb192/reddit-buddy-mcp](https://github.com/karanb192/reddit-buddy-mcp) ⭐ 103 | 🐛 3 | 🌐 TypeScript | 📅 2025-10-22 📇 🏠 - Browse Reddit posts, search content, and analyze user activity without API keys. Works out-of-the-box with Claude Desktop.
* [HagaiHen/facebook-mcp-server](https://github.com/HagaiHen/facebook-mcp-server) ⭐ 56 | 🐛 0 | 🌐 Python | 📅 2025-08-20 🐍 ☁️ - Integrates with Facebook Pages to enable direct management of posts, comments, and engagement metrics through the Graph API for streamlined social media management.
* [kunallunia/twitter-mcp](https://github.com/LuniaKunal/mcp-twitter) ⭐ 43 | 🐛 2 | 🌐 Python | 📅 2025-05-03 🐍 🏠 - All-in-one Twitter management solution providing timeline access, user tweet retrieval, hashtag monitoring, conversation analysis, direct messaging, sentiment analysis of a post, and complete post lifecycle control - all through a streamlined API.
* [anwerj/youtube-uploader-mcp](https://github.com/anwerj/youtube-uploader-mcp) ⭐ 27 | 🐛 1 | 🌐 Go | 📅 2025-10-11 🏎️ ☁️ - AI‑powered YouTube uploader—no CLI, no YouTube Studio. Uploade videos directly from MCP clients with all AI capabilities.
* [macrocosm-os/macrocosmos-mcp](https://github.com/macrocosm-os/macrocosmos-mcp) ⭐ 21 | 🐛 0 | 🌐 Python | 📅 2025-09-30 - 🎖️ 🐍 ☁️ Access real-time X/Reddit/YouTube data directly in your LLM applications  with search phrases, users, and date filtering.
* [gwbischof/bluesky-social-mcp](https://github.com/gwbischof/bluesky-social-mcp) ⭐ 10 | 🐛 3 | 🌐 Python | 📅 2025-05-23 🐍 🏠 - An MCP server for interacting with Bluesky via the atproto client.
* [sinanefeozler/reddit-summarizer-mcp](https://github.com/sinanefeozler/reddit-summarizer-mcp) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2025-08-05 🐍 🏠 ☁️ - MCP server for summarizing users's Reddit homepage or any subreddit based on posts and comments.

### 🏃 <a name="sports"></a>Sports

Tools for accessing sports-related data, results, and statistics.

* [r-huijts/strava-mcp](https://github.com/r-huijts/strava-mcp) ⭐ 162 | 🐛 4 | 🌐 TypeScript | 📅 2025-09-17 📇 ☁️ - A Model Context Protocol (MCP) server that connects to Strava API, providing tools to access Strava data through LLMs
* [guillochon/mlb-api-mcp](https://github.com/guillochon/mlb-api-mcp) ⭐ 32 | 🐛 2 | 🌐 Python | 📅 2025-07-29 🐍 🏠 - MCP server that acts as a proxy to the freely available MLB API, which provides player info, stats, and game information.
* [mikechao/balldontlie-mcp](https://github.com/mikechao/balldontlie-mcp) ⭐ 17 | 🐛 1 | 🌐 JavaScript | 📅 2025-07-17 📇 - MCP server that integrates balldontlie api to provide information about players, teams and games for the NBA, NFL and MLB
* [r-huijts/firstcycling-mcp](https://github.com/r-huijts/firstcycling-mcp) ⭐ 15 | 🐛 2 | 🌐 Python | 📅 2025-08-26 📇 ☁️ - Access cycling race data, results, and statistics through natural language. Features include retrieving start lists, race results, and rider information from firstcycling.com.
* [RobSpectre/mvf1](https://github.com/RobSpectre/mvf1) ⭐ 14 | 🐛 1 | 🌐 Python | 📅 2025-07-05 🐍 ☁️ - MCP server that controls [MultiViewer](https://multiviewer.app), an app for watching motorsports like Formula 1, World Endurance Championship, IndyCar and others.
* [willvelida/mcp-afl-server](https://github.com/willvelida/mcp-afl-server) ⭐ 12 | 🐛 4 | 🌐 C# | 📅 2025-09-08 ☁️ - MCP server that integrates with the Squiggle API to provide information on Australian Football League teams, ladder standings, results, tips, and power rankings.
* [cloudbet/sports-mcp-server](https://github.com/cloudbet/sports-mcp-server) ⭐ 8 | 🐛 1 | 🌐 Go | 📅 2025-07-07 🏎️ ☁️ – Access structured sports data via the Cloudbet API. Query upcoming events, live odds, stake limits, and market info across soccer, basketball, tennis, esports, and more.

### 🎧 <a name="support-and-service-management"></a>Support & Service Management

Tools for managing customer support, IT service management, and helpdesk operations.

* [sooperset/mcp-atlassian](https://github.com/sooperset/mcp-atlassian) ⭐ 3,407 | 🐛 145 | 🌐 Python | 📅 2025-06-30 🐍 ☁️ - MCP server for Atlassian products (Confluence and Jira). Supports Confluence Cloud, Jira Cloud, and Jira Server/Data Center. Provides comprehensive tools for searching, reading, creating, and managing content across Atlassian workspaces.
* [nguyenvanduocit/jira-mcp](https://github.com/nguyenvanduocit/jira-mcp) ⭐ 65 | 🐛 1 | 🌐 Go | 📅 2025-10-21 🏎️ ☁️ - A Go-based MCP connector for Jira that enables AI assistants like Claude to interact with Atlassian Jira. This tool provides a seamless interface for AI models to perform common Jira operations including issue management, sprint planning, and workflow transitions.
* [effytech/freshdesk-mcp](https://github.com/effytech/freshdesk_mcp) ⭐ 29 | 🐛 1 | 🌐 Python | 📅 2025-10-06 🐍 ☁️ - MCP server that integrates with Freshdesk, enabling AI models to interact with Freshdesk modules and perform various support operations.
* [aikts/yandex-tracker-mcp](https://github.com/aikts/yandex-tracker-mcp) ⭐ 25 | 🐛 7 | 🌐 Python | 📅 2025-10-06 🐍 ☁️ 🏠 - MCP Server for Yandex Tracker. Provides tools for searching and retrieving information about issues, queues, users.
* [incentivai/quickchat-ai-mcp](https://github.com/incentivai/quickchat-ai-mcp) ⭐ 20 | 🐛 5 | 🌐 Python | 📅 2025-09-19 🐍 🏠 ☁️ - Launch your conversational Quickchat AI agent as an MCP to give AI apps real-time access to its Knowledge Base and conversational capabilities.
* [tom28881/mcp-jira-server](https://github.com/tom28881/mcp-jira-server) ⭐ 4 | 🐛 3 | 🌐 TypeScript | 📅 2025-06-25 📇 ☁️ 🏠 - Comprehensive TypeScript MCP server for Jira with 20+ tools covering complete project management workflow: issue CRUD, sprint management, comments/history, attachments, batch operations.

### 🌎 <a name="translation-services"></a>Translation Services

Translation tools and services to enable AI assistants to translate content between different languages.

* [translated/lara-mcp](https://github.com/translated/lara-mcp) ⭐ 76 | 🐛 1 | 🌐 TypeScript | 📅 2025-10-06 🎖️ 📇 ☁️ - MCP Server for Lara Translate API, enabling powerful translation capabilities with support for language detection and context-aware translations.
* [mmntm/weblate-mcp](https://github.com/mmntm/weblate-mcp) ⭐ 8 | 🐛 2 | 🌐 TypeScript | 📅 2025-08-06 📇 ☁️ - Comprehensive Model Context Protocol server for Weblate translation management, enabling AI assistants to perform translation tasks, project management, and content discovery with smart format transformations.

### 🎧 <a name="text-to-speech"></a>Text-to-Speech

Tools for converting text-to-speech and vice-versa

* [mbailey/voice-mcp](https://github.com/mbailey/voice-mcp) ⭐ 393 | 🐛 17 | 🌐 Python | 📅 2025-10-23 🐍 🏠 - Complete voice interaction server supporting speech-to-text, text-to-speech, and real-time voice conversations through local microphone, OpenAI-compatible APIs, and LiveKit integration
* [mberg/kokoro-tts-mcp](https://github.com/mberg/kokoro-tts-mcp) ⭐ 61 | 🐛 3 | 🌐 Python | 📅 2025-09-12 🐍 🏠 - MCP Server that uses the open weight Kokoro TTS models to convert text-to-speech. Can convert text to MP3 on a local driver or auto-upload to an S3 bucket.
* [daisys-ai/daisys-mcp](https://github.com/daisys-ai/daisys-mcp) ⭐ 10 | 🐛 2 | 🌐 Python | 📅 2025-07-31 🐍 🏠 🍎 🪟 🐧 - Generate high-quality text-to-speech and text-to-voice outputs using the [DAISYS](https://www.daisys.ai/) platform and make it able to play and store audio generated.
* [transcribe-app/mcp-transcribe](https://github.com/transcribe-app/mcp-transcribe) ⭐ 2 | 🐛 0 | 🌐 JavaScript | 📅 2025-10-08 📇 🏠 - This service provides fast and reliable transcriptions for audio/video files and voice memos. It allows LLMs to interact with the text content of audio/video file.

### 🚆 <a name="travel-and-transportation"></a>Travel & Transportation

Access to travel and transportation information. Enables querying schedules, routes, and real-time travel data.

* [openbnb-org/mcp-server-airbnb](https://github.com/openbnb-org/mcp-server-airbnb) ⭐ 316 | 🐛 6 | 🌐 JavaScript | 📅 2025-07-18 📇 ☁️ - Provides tools to search Airbnb and get listing details.
* [cobanov/teslamate-mcp](https://github.com/cobanov/teslamate-mcp) ⭐ 103 | 🐛 1 | 🌐 Python | 📅 2025-08-18 🐍 🏠 - A Model Context Protocol (MCP) server that provides access to your TeslaMate database, allowing AI assistants to query Tesla vehicle data and analytics.
* [pab1it0/tripadvisor-mcp](https://github.com/pab1it0/tripadvisor-mcp) ⭐ 47 | 🐛 3 | 🌐 Python | 📅 2025-04-13 📇 🐍 - A MCP server that enables LLMs to interact with Tripadvisor API, supporting location data, reviews, and photos through standardized MCP interfaces
* [r-huijts/ns-mcp-server](https://github.com/r-huijts/ns-mcp-server) ⭐ 43 | 🐛 2 | 🌐 TypeScript | 📅 2025-08-26 📇 ☁️ - Access Dutch Railways (NS) travel information, schedules, and real-time updates
* [KyrieTangSheng/mcp-server-nationalparks](https://github.com/KyrieTangSheng/mcp-server-nationalparks) ⭐ 33 | 🐛 5 | 🌐 TypeScript | 📅 2025-06-17 📇 ☁️ - National Park Service API integration providing latest information of park details, alerts, visitor centers, campgrounds, and events for U.S. National Parks
* [campertunity/mcp-server](https://github.com/campertunity/mcp-server) ⭐ 11 | 🐛 0 | 🌐 TypeScript | 📅 2025-05-19 🎖️ 📇 🏠 - Search campgrounds around the world on campertunity, check availability, and provide booking links
* [Pradumnasaraf/aviationstack-mcp](https://github.com/Pradumnasaraf/aviationstack-mcp) ⭐ 11 | 🐛 2 | 🌐 Python | 📅 2025-07-25 🐍 ☁️ 🍎 🪟 🐧 - An MCP server using the AviationStack API to fetch real-time flight data including airline flights, airport schedules, future flights and aircraft types.
* [srinath1510/alltrails-mcp-server](https://github.com/srinath1510/alltrails-mcp-server) ⭐ 6 | 🐛 2 | 🌐 Python | 📅 2025-06-19 🐍 ☁️ - A MCP server that provides access to AllTrails data, allowing you to search for hiking trails and get detailed trail information
* [helpful-AIs/triplyfy-mcp](https://github.com/helpful-AIs/triplyfy-mcp) ⭐ 3 | 🐛 0 | 📅 2025-08-25 📇 ☁️ - An MCP server that lets LLMs plan and manage itineraries with interactive maps in Triplyfy; manage itineraries, places and notes, and search/save flights.
* [skedgo/tripgo-mcp-server](https://github.com/skedgo/tripgo-mcp-server) ⭐ 2 | 🐛 1 | 🌐 TypeScript | 📅 2025-10-06 📇 ☁️ - Provides tools from the TripGo API for multi-modal trip planning, transport locations, and public transport departures, including real-time information.
* [lucygoodchild/mcp-national-rail](https://github.com/lucygoodchild/mcp-national-rail) ⭐ 1 | 🐛 2 | 🌐 TypeScript | 📅 2025-06-02 📇 ☁️ - An MCP server for UK National Rail trains service, providing train schedules and live travel information, intergrating the Realtime Trains API

### 🔄 <a name="version-control"></a>Version Control

Interact with Git repositories and version control platforms. Enables repository management, code analysis, pull request handling, issue tracking, and other version control operations through standardized APIs.

* [modelcontextprotocol/server-git](https://github.com/modelcontextprotocol/servers/tree/main/src/git) ⭐ 71,117 | 🐛 277 | 🌐 TypeScript | 📅 2025-10-24 🐍 🏠 - Direct Git repository operations including reading, searching, and analyzing local repositories
* [modelcontextprotocol/server-gitlab](https://github.com/modelcontextprotocol/servers/tree/main/src/gitlab) ⭐ 71,117 | 🐛 277 | 🌐 TypeScript | 📅 2025-10-24 📇 ☁️ 🏠 - GitLab platform integration for project management and CI/CD operations
* [github/github-mcp-server](https://github.com/github/github-mcp-server) ⭐ 23,847 | 🐛 274 | 🌐 Go | 📅 2025-10-24 📇 ☁️ - Official GitHub server for integration with repository management, PRs, issues, and more.
* [Tiberriver256/mcp-server-azure-devops](https://github.com/Tiberriver256/mcp-server-azure-devops) ⭐ 304 | 🐛 33 | 🌐 TypeScript | 📅 2025-09-23 📇 ☁️ - Azure DevOps integration for repository management, work items, and pipelines.
* [adhikasp/mcp-git-ingest](https://github.com/adhikasp/mcp-git-ingest) ⭐ 282 | 🐛 10 | 🌐 Python | 📅 2025-01-26 🐍 🏠 - Read and analyze GitHub repositories with your LLM
* [kopfrechner/gitlab-mr-mcp](https://github.com/kopfrechner/gitlab-mr-mcp) ⭐ 64 | 🐛 7 | 🌐 JavaScript | 📅 2025-10-20 📇 ☁️ - Interact seamlessly with issues and merge requests of your GitLab projects.
* [ddukbg/github-enterprise-mcp](https://github.com/ddukbg/github-enterprise-mcp) ⭐ 25 | 🐛 0 | 🌐 TypeScript | 📅 2025-09-14 📇 ☁️ 🏠 - MCP server for GitHub Enterprise API integration
* [QuentinCody/github-graphql-mcp-server](https://github.com/QuentinCody/github-graphql-mcp-server) ⭐ 8 | 🐛 1 | 🌐 Python | 📅 2025-08-17 🐍 ☁️ - Unofficial GitHub MCP server that provides access to GitHub's GraphQL API, enabling more powerful and flexible queries for repository data, issues, pull requests, and other GitHub resources.
* [kaiyuanxiaobing/atomgit-mcp-server](https://github.com/kaiyuanxiaobing/atomgit-mcp-server) ⭐ 7 | 🐛 2 | 🌐 TypeScript | 📅 2025-07-17 📇 ☁️ - Official AtomGit server for integration with repository management, PRs, issues, branches, labels, and more.
* [theonedev/tod](https://github.com/theonedev/tod/blob/main/mcp.md) ⭐ 2 | 🐛 0 | 🌐 Go | 📅 2025-09-29 🏎️ 🏠 - A MCP server for OneDev for CI/CD pipeline editing, issue workflow automation, and pull request review
* [gitea/gitea-mcp](https://gitea.com/gitea/gitea-mcp) 🎖️ 🏎️ ☁️ 🏠 🍎 🪟 🐧 - Interactive with Gitea instances with MCP.

### 🏢 <a name="workplace-and-productivity"></a>Workplace & Productivity

* [taylorwilsdon/google\_workspace\_mcp](https://github.com/taylorwilsdon/google_workspace_mcp) ⭐ 819 | 🐛 30 | 🌐 Python | 📅 2025-10-19 🐍 ☁️ 🍎 🪟 🐧 - Comprehensive Google Workspace MCP server with full support for Google Calendar, Drive, Gmail, and Docs, Forms, Chats, Slides and Sheets over stdio, Streamable HTTP and SSE transports.
* [MarkusPfundstein/mcp-gsuite](https://github.com/MarkusPfundstein/mcp-gsuite) ⭐ 453 | 🐛 22 | 🌐 Python | 📅 2025-04-14 🐍 ☁️ - Integration with gmail and Google Calendar.
* [takumi0706/google-calendar-mcp](https://github.com/takumi0706/google-calendar-mcp) ⭐ 53 | 🐛 2 | 🌐 TypeScript | 📅 2025-10-22 📇 ☁️ - An MCP server to interface with the Google Calendar API. Based on TypeScript.
* [giuseppe-coco/Google-Workspace-MCP-Server](https://github.com/giuseppe-coco/Google-Workspace-MCP-Server) ⭐ 19 | 🐛 2 | 🌐 Python | 📅 2025-07-11 🐍 ☁️ 🍎 🪟 🐧 - MCP server that seamlessly interacts with your Google Calendar, Gmail, Drive and so on.
* [bivex/kanboard-mcp](https://github.com/bivex/kanboard-mcp) ⭐ 13 | 🐛 0 | 🌐 Go | 📅 2025-08-06 🏎️ ☁️ 🏠 - A Model Context Protocol (MCP) server written in Go that empowers AI agents and Large Language Models (LLMs) to seamlessly interact with Kanboard. It transforms natural language commands into Kanboard API calls, enabling intelligent automation of project, task, and user management, streamlining workflows, and enhancing productivity.
* [vakharwalad23/google-mcp](https://github.com/vakharwalad23/google-mcp) ⭐ 12 | 🐛 1 | 🌐 TypeScript | 📅 2025-09-15 📇 ☁️ - Collection of Google-native tools (Gmail, Calendar, Drive, Tasks) for MCP with OAuth management, automated token refresh, and auto re-authentication capabilities.
* [teamwork/mcp](https://github.com/teamwork/mcp) ⭐ 9 | 🐛 4 | 🌐 Go | 📅 2025-10-23 🎖️ 🏎️ ☁️ 🍎 🪟 🐧 - Project and resource management platform that keeps your client projects on track, makes managing resources a breeze, and keeps your profits on point.
* [tubasasakunn/context-apps-mcp](https://github.com/tubasasakunn/context-apps-mcp) ⭐ 4 | 🐛 1 | 📅 2025-07-26 📇 🏠 🍎 🪟 🐧 - AI-powered productivity suite connecting Todo, Idea, Journal, and Timer apps with Claude via Model Context Protocol.

### 🛠️ <a name="other-tools-and-integrations"></a>Other Tools and Integrations

* [modelcontextprotocol/server-everything](https://github.com/modelcontextprotocol/servers/tree/main/src/everything) ⭐ 71,117 | 🐛 277 | 🌐 TypeScript | 📅 2025-10-24 📇 🏠 - MCP server that exercises all the features of the MCP protocol
* [mediar-ai/screenpipe](https://github.com/mediar-ai/screenpipe) ⭐ 15,811 | 🐛 217 | 🌐 TypeScript | 📅 2025-09-01 - 🎖️ 🦀 🏠 🍎 Local-first system capturing screen/audio with timestamped indexing, SQL/embedding storage, semantic search, LLM-powered history analysis, and event-triggered actions - enables building context-aware AI agents through a NextJS plugin ecosystem.
* [Klavis-AI/YouTube](https://github.com/Klavis-AI/klavis/tree/main/mcp_servers/youtube) ⭐ 5,295 | 🐛 44 | 🌐 Python | 📅 2025-10-23 🐍 📇 - Extract and convert YouTube video information.
* [sooperset/mcp-atlassian](https://github.com/sooperset/mcp-atlassian) ⭐ 3,407 | 🐛 145 | 🌐 Python | 📅 2025-06-30 🐍 ☁️ - MCP server for Atlassian products (Confluence and Jira). Supports Confluence Cloud, Jira Cloud, and Jira Server/Data Center. Provides comprehensive tools for searching, reading, creating, and managing content across Atlassian workspaces.
* [MarkusPfundstein/mcp-obsidian](https://github.com/MarkusPfundstein/mcp-obsidian) ⭐ 2,305 | 🐛 60 | 🌐 Python | 📅 2025-06-28 🐍 ☁️ 🏠 - Interacting with Obsidian via REST API
* [chrishayuk/mcp-cli](https://github.com/chrishayuk/mcp-cli) ⭐ 1,737 | 🐛 20 | 🌐 Python | 📅 2025-10-19 🐍 🏠 - Yet another CLI tool for testing MCP servers
* [anaisbetts/mcp-installer](https://github.com/anaisbetts/mcp-installer) ⭐ 1,450 | 🐛 17 | 🌐 JavaScript | 📅 2024-11-26 🐍 🏠 -  An MCP server that installs other MCP servers for you.
* [calclavia/mcp-obsidian](https://github.com/calclavia/mcp-obsidian) ⭐ 1,177 | 🐛 16 | 🌐 JavaScript | 📅 2025-08-15 📇 🏠 - This is a connector to allow Claude Desktop (or any MCP client) to read and search any directory containing Markdown notes (such as an Obsidian vault).
* [Azure/azure-mcp](https://github.com/Azure/azure-mcp) ⚠️ Archived - Official Microsoft MCP server for Azure services including Storage, Cosmos DB, and Azure Monitor.
* [caol64/wenyan-mcp](https://github.com/caol64/wenyan-mcp) ⭐ 882 | 🐛 23 | 🌐 JavaScript | 📅 2025-10-15 📇 🏠 🍎 🪟 🐧 - Wenyan MCP Server, which lets AI automatically format Markdown articles and publish them to WeChat GZH.
* [suekou/mcp-notion-server](https://github.com/suekou/mcp-notion-server) ⭐ 827 | 🐛 14 | 🌐 TypeScript | 📅 2025-05-14 📇 🏠 - Interacting with Notion API
* [rusiaaman/wcgw](https://github.com/rusiaaman/wcgw/blob/main/src/wcgw/client/mcp_server/Readme.md) ⭐ 605 | 🐛 5 | 🌐 Python | 📅 2025-10-09 🐍 🏠 - Autonomous shell execution, computer control and coding agent. (Mac)
* [apify/actors-mcp-server](https://github.com/apify/actors-mcp-server) ⭐ 480 | 🐛 23 | 🌐 TypeScript | 📅 2025-10-23 📇 ☁️ - Use 3,000+ pre-built cloud tools, known as Actors, to extract data from websites, e-commerce, social media, search engines, maps, and more
* [anaisbetts/mcp-youtube](https://github.com/anaisbetts/mcp-youtube) ⭐ 465 | 🐛 12 | 🌐 JavaScript | 📅 2025-03-20 📇 ☁️ - Fetch YouTube subtitles
* [tevonsb/homeassistant-mcp](https://github.com/tevonsb/homeassistant-mcp) ⭐ 450 | 🐛 16 | 🌐 TypeScript | 📅 2025-02-01 📇 🏠 - Access Home Assistant data and control devices (lights, switches, thermostats, etc).
* [wong2/mcp-cli](https://github.com/wong2/mcp-cli) ⭐ 389 | 🐛 10 | 🌐 JavaScript | 📅 2025-08-13 📇 🏠 - CLI tool for testing MCP servers
* [evalstate/mcp-hfspace](https://github.com/evalstate/mcp-hfspace) ⭐ 365 | 🐛 12 | 🌐 TypeScript | 📅 2025-06-13 📇 ☁️ - Use HuggingFace Spaces directly from Claude. Use Open Source Image Generation, Chat, Vision tasks and more. Supports Image, Audio and text uploads/downloads.
* [blurrah/mcp-graphql](https://github.com/blurrah/mcp-graphql) ⭐ 307 | 🐛 12 | 🌐 TypeScript | 📅 2025-09-08 📇 ☁️ - Allows the AI to query GraphQL servers
* [ttommyth/interactive-mcp](https://github.com/ttommyth/interactive-mcp) ⭐ 305 | 🐛 8 | 🌐 TypeScript | 📅 2025-09-09 📇 🏠 🍎 🪟 🐧 - Enables interactive LLM workflows by adding local user prompts and chat capabilities directly into the MCP loop.
* [PV-Bhat/vibe-check-mcp-server](https://github.com/PV-Bhat/vibe-check-mcp-server) ⭐ 280 | 🐛 6 | 🌐 TypeScript | 📅 2025-10-23 📇 ☁️ - An MCP server that prevents cascading errors and scope creep by calling a "Vibe-check" agent to ensure user alignment.
* [zueai/mcp-manager](https://github.com/zueai/mcp-manager) ⭐ 266 | 🐛 3 | 🌐 TypeScript | 📅 2024-12-21 📇 ☁️ - Simple Web UI to install and manage MCP servers for Claude Desktop App.
* [danhilse/notion\_mcp](https://github.com/danhilse/notion_mcp) ⭐ 202 | 🐛 6 | 🌐 Python | 📅 2024-12-18 🐍 ☁️ - Integrates with Notion's API to manage personal todo lists
* [quarkiverse/mcp-server-jfx](https://github.com/quarkiverse/quarkus-mcp-servers/tree/main/jfx) ⭐ 172 | 🐛 24 | 🌐 Java | 📅 2025-07-28 ☕ 🏠 - Draw on JavaFX canvas.
* [marcelmarais/Spotify](https://github.com/marcelmarais/spotify-mcp-server) ⭐ 171 | 🐛 8 | 🌐 TypeScript | 📅 2025-09-27 - 📇 🏠 Control Spotify playback and manage playlists.
* [pyroprompts/any-chat-completions-mcp](https://github.com/pyroprompts/any-chat-completions-mcp) ⭐ 141 | 🐛 6 | 🌐 JavaScript | 📅 2025-05-01 - Chat with any other OpenAI SDK Compatible Chat Completions API, like Perplexity, Groq, xAI and more
* [integromat/make-mcp-server](https://github.com/integromat/make-mcp-server) ⭐ 140 | 🐛 6 | 🌐 TypeScript | 📅 2025-10-22 🎖️ 📇 🏠 - Turn your [Make](https://www.make.com/) scenarios into callable tools for AI assistants.
* [githejie/mcp-server-calculator](https://github.com/githejie/mcp-server-calculator) ⭐ 130 | 🐛 6 | 🌐 Python | 📅 2025-05-10 🐍 🏠 - This server enables LLMs to use calculator for precise numerical calculations
* [sirmews/apple-notes-mcp](https://github.com/sirmews/apple-notes-mcp) ⚠️ Archived 🐍 🏠 - Allows the AI to read from your local Apple Notes database (macOS only)
* [tacticlaunch/mcp-linear](https://github.com/tacticlaunch/mcp-linear) ⭐ 111 | 🐛 6 | 🌐 TypeScript | 📅 2025-09-05 📇 ☁️ 🍎 🪟 🐧 - Integrates with Linear project management system
* [Seym0n/tiktok-mcp](https://github.com/Seym0n/tiktok-mcp) ⭐ 110 | 🐛 1 | 🌐 JavaScript | 📅 2025-08-25 📇 ☁️ - Interact with TikTok videos
* [roychri/mcp-server-asana](https://github.com/roychri/mcp-server-asana) ⭐ 104 | 🐛 11 | 🌐 TypeScript | 📅 2025-05-21 - 📇 ☁️ This Model Context Protocol server implementation of Asana allows you to talk to Asana API from MCP Client such as Anthropic's Claude Desktop Application, and many more.
* [ivnvxd/mcp-server-odoo](https://github.com/ivnvxd/mcp-server-odoo) ⭐ 94 | 🐛 11 | 🌐 Python | 📅 2025-10-13 🐍 ☁️/🏠 - Connect AI assistants to Odoo ERP systems for business data access, record management, and workflow automation.
* [evalstate/mcp-miro](https://github.com/evalstate/mcp-miro) ⭐ 91 | 🐛 7 | 🌐 TypeScript | 📅 2024-12-23 📇 ☁️ - Access MIRO whiteboards, bulk create and read items. Requires OAUTH key for REST API.
* [isaacwasserman/mcp-vegalite-server](https://github.com/isaacwasserman/mcp-vegalite-server) ⭐ 89 | 🐛 3 | 🌐 Python | 📅 2025-05-16 🐍 🏠 - Generate visualizations from fetched data using the VegaLite format and renderer.
* [nguyenvanduocit/all-in-one-model-context-protocol](https://github.com/nguyenvanduocit/all-in-one-model-context-protocol) ⭐ 89 | 🐛 2 | 📅 2025-02-24 🏎️ 🏠 - Some useful tools for developer, almost everything an engineer need: confluence, Jira, Youtube, run script, knowledge base RAG, fetch URL, Manage youtube channel, emails, calendar, gitlab
* [mrjoshuak/godoc-mcp](https://github.com/mrjoshuak/godoc-mcp) ⭐ 87 | 🐛 3 | 🌐 Go | 📅 2025-06-25 🏎️ 🏠 - Token-efficient Go documentation server that provides AI assistants with smart access to package docs and types without reading entire source files
* [tanigami/mcp-server-perplexity](https://github.com/tanigami/mcp-server-perplexity) ⭐ 83 | 🐛 3 | 🌐 Python | 📅 2024-12-25 🐍 ☁️ - Interacting with Perplexity API.
* [wanaku-ai/wanaku](https://github.com/wanaku-ai/wanaku) ⭐ 83 | 🐛 76 | 🌐 Java | 📅 2025-10-22 - ☁️ 🏠 The Wanaku MCP Router is a SSE-based MCP server that provides an extensible routing engine that allows integrating your enterprise systems with AI agents.
* [Rai220/think-mcp](https://github.com/Rai220/think-mcp) ⭐ 78 | 🐛 1 | 🌐 Python | 📅 2025-04-16 🐍 🏠 - Enhances any agent's reasoning capabilities by integrating the think-tools, as described in [Anthropic's article](https://www.anthropic.com/engineering/claude-think-tool).
* [pierrebrunelle/mcp-server-openai](https://github.com/pierrebrunelle/mcp-server-openai) ⭐ 74 | 🐛 6 | 🌐 Python | 📅 2024-11-28 🐍 ☁️ - Query OpenAI models directly from Claude using MCP protocol
* [johannesbrandenburger/typst-mcp](https://github.com/johannesbrandenburger/typst-mcp) ⭐ 72 | 🐛 3 | 🌐 Python | 📅 2025-08-05 🐍 🏠 - MCP server for Typst, a markup-based typesetting system. It provides tools for converting between LaTeX and Typst, validating Typst syntax, and generating images from Typst code.
* [mzxrai/mcp-openai](https://github.com/mzxrai/mcp-openai) ⭐ 68 | 🐛 7 | 🌐 JavaScript | 📅 2024-12-06 📇 ☁️ - Chat with OpenAI's smartest models
* [AbdelStark/bitcoin-mcp](https://github.com/AbdelStark/bitcoin-mcp) ⭐ 65 | 🐛 1 | 🌐 TypeScript | 📅 2025-08-01 - ₿ A Model Context Protocol (MCP) server that enables AI models to interact with Bitcoin, allowing them to generate keys, validate addresses, decode transactions, query the blockchain, and more.
* [hiromitsusasaki/raindrop-io-mcp-server](https://github.com/hiromitsusasaki/raindrop-io-mcp-server) ⭐ 62 | 🐛 17 | 🌐 TypeScript | 📅 2025-06-04 📇 ☁️ - An integration that allows LLMs to interact with Raindrop.io bookmarks using the Model Context Protocol (MCP).
* [SecretiveShell/MCP-wolfram-alpha](https://github.com/SecretiveShell/MCP-wolfram-alpha) ⭐ 62 | 🐛 1 | 🌐 Python | 📅 2025-08-18 🐍 ☁️ - An MCP server for querying wolfram alpha API.
* [allenporter/mcp-server-home-assistant](https://github.com/allenporter/mcp-server-home-assistant) ⚠️ Archived 🐍 🏠 - Expose all Home Assistant voice intents through a Model Context Protocol Server allowing home control.
* [apinetwork/piapi-mcp-server](https://github.com/apinetwork/piapi-mcp-server) ⭐ 61 | 🐛 5 | 🌐 TypeScript | 📅 2025-08-15 📇 ☁️ PiAPI MCP server makes users able to generate media content with Midjourney/Flux/Kling/Hunyuan/Udio/Trellis directly from Claude or any other MCP-compatible apps.
* [ivo-toby/contentful-mcp](https://github.com/ivo-toby/contentful-mcp) ⭐ 61 | 🐛 10 | 🌐 TypeScript | 📅 2025-10-08 📇 🏠 - Update, create, delete content, content-models and assets in your Contentful Space
* [inkbytefo/screenmonitormcp](https://github.com/inkbytefo/screenmonitormcp) ⚠️ Archived 🐍 🏠 🍎 🪟 🐧 - Real-time screen analysis, context-aware recording, and UI monitoring MCP server. Supports AI vision, event hooks, and multimodal agent workflows.
* [gotoolkits/DifyWorkflow](https://github.com/gotoolkits/mcp-difyworkflow-server) ⭐ 58 | 🐛 2 | 🌐 Go | 📅 2024-12-26 - 🏎️ ☁️ Tools to the query and execute of Dify workflows
* [rember/rember-mcp](https://github.com/rember/rember-mcp) ⭐ 57 | 🐛 3 | 🌐 TypeScript | 📅 2025-03-28 📇 🏠 - Create spaced repetition flashcards in [Rember](https://rember.com) to remember anything you learn in your chats.
* [NON906/omniparser-autogui-mcp](https://github.com/NON906/omniparser-autogui-mcp) ⭐ 56 | 🐛 4 | 🌐 Python | 📅 2025-03-02 - 🐍 Automatic operation of on-screen GUI.
* [k-jarzyna/mcp-miro](https://github.com/k-jarzyna/mcp-miro) ⭐ 54 | 🐛 1 | 🌐 TypeScript | 📅 2025-08-19 📇 ☁️ - Miro MCP server, exposing all functionalities available in official Miro SDK
* [awkoy/replicate-flux-mcp](https://github.com/awkoy/replicate-flux-mcp) ⭐ 50 | 🐛 1 | 🌐 TypeScript | 📅 2025-08-06 📇 ☁️ - Provides the ability to generate images via Replicate's API.
* [feuerdev/keep-mcp](https://github.com/feuerdev/keep-mcp) ⭐ 50 | 🐛 3 | 🌐 Python | 📅 2025-04-12 🐍 ☁️ - Read, create, update and delete Google Keep notes.
* [Mtehabsim/ScreenPilot](https://github.com/Mtehabsim/ScreenPilot) ⭐ 46 | 🐛 2 | 🌐 Python | 📅 2025-08-15 🐍 🏠 - enables AI to fully control and access GUI interactions by providing tools for mouse and keyboard, ideal for general automation, education, and experimentation.
* [NakaokaRei/swift-mcp-gui](https://github.com/NakaokaRei/swift-mcp-gui.git) ⭐ 45 | 🐛 8 | 🌐 Swift | 📅 2025-07-26 🏠 🍎 - MCP server that can execute commands such as keyboard input and mouse movement
* [yuna0x0/hackmd-mcp](https://github.com/yuna0x0/hackmd-mcp) ⭐ 41 | 🐛 0 | 🌐 TypeScript | 📅 2025-10-20 📇 ☁️ - Allows AI models to interact with [HackMD](https://hackmd.io)
* [akseyh/bear-mcp-server](https://github.com/akseyh/bear-mcp-server) ⭐ 40 | 🐛 2 | 🌐 JavaScript | 📅 2025-05-26 - Allows the AI to read from your Bear Notes (macOS only)
* [kenliao94/mcp-server-rabbitmq](https://github.com/kenliao94/mcp-server-rabbitmq) ⭐ 40 | 🐛 7 | 🌐 Python | 📅 2025-10-14 🐍 🏠 - Enable interaction (admin operation, message enqueue/dequeue) with RabbitMQ
* [amidabuddha/unichat-mcp-server](https://github.com/amidabuddha/unichat-mcp-server) ⭐ 36 | 🐛 1 | 🌐 Python | 📅 2025-08-05 🐍/📇 ☁️ - Send requests to OpenAI, MistralAI, Anthropic, xAI, Google AI or DeepSeek using MCP protocol via tool or predefined prompts. Vendor API key required
* [andybrandt/mcp-simple-openai-assistant](https://github.com/andybrandt/mcp-simple-openai-assistant) ⭐ 36 | 🐛 1 | 🌐 Python | 📅 2025-09-12 - 🐍 ☁️  MCP to talk to OpenAI assistants (Claude can use any GPT model as his assitant)
* [pskill9/hn-server](https://github.com/pskill9/hn-server) ⭐ 35 | 🐛 2 | 🌐 JavaScript | 📅 2024-12-31 - 📇 ☁️ Parses the HTML content from news.ycombinator.com (Hacker News) and provides structured data for different types of stories (top, new, ask, show, jobs).
* [jen6/ticktick-mcp](https://github.com/jen6/ticktick-mcp) ⭐ 33 | 🐛 2 | 🌐 Python | 📅 2025-07-23 🐍 ☁️ - [TickTick](https://ticktick.com/) MCP server. Built upon the ticktick-py library, it offers significantly improved filtering capabilities.
* [orellazi/coda-mcp](https://github.com/orellazri/coda-mcp) ⭐ 33 | 🐛 0 | 🌐 TypeScript | 📅 2025-08-24 📇 ☁️ - MCP server for [Coda](https://coda.io/)
* [awwaiid/mcp-server-taskwarrior](https://github.com/awwaiid/mcp-server-taskwarrior) ⭐ 32 | 🐛 4 | 🌐 JavaScript | 📅 2025-03-16 🏠 📇 - An MCP server for basic local taskwarrior usage (add, update, remove tasks)
* [kelvin6365/plane-mcp-server](https://github.com/kelvin6365/plane-mcp-server) ⭐ 32 | 🐛 2 | 🌐 JavaScript | 📅 2025-08-22 - 🏎️ 🏠 This MCP Server will help you to manage projects and issues through [Plane's](https://plane.so) API
* [tomekkorbak/oura-mcp-server](https://github.com/tomekkorbak/oura-mcp-server) ⭐ 32 | 🐛 4 | 🌐 Python | 📅 2025-02-27 🐍 ☁️ - An MCP server for Oura, an app for tracking sleep
* [danielkennedy1/pdf-tools-mcp](https://github.com/danielkennedy1/pdf-tools-mcp) ⭐ 31 | 🐛 3 | 🌐 Python | 📅 2025-05-17 🐍 - PDF download, view & manipulation utilities.
* [esignaturescom/mcp-server-esignatures](https://github.com/esignaturescom/mcp-server-esignatures) ⭐ 30 | 🐛 4 | 🌐 Python | 📅 2025-10-01 🐍 ☁️️ - Contract and template management for drafting, reviewing, and sending binding contracts via the eSignatures API.
* [HenryHaoson/Yuque-MCP-Server](https://github.com/HenryHaoson/Yuque-MCP-Server) ⭐ 28 | 🐛 4 | 🌐 TypeScript | 📅 2025-04-22 - 📇 ☁️ A Model-Context-Protocol (MCP) server for integrating with Yuque API, allowing AI models to manage documents, interact with knowledge bases, search content, and access analytics data from the Yuque platform.
* [Badhansen/notion-mcp](https://github.com/Badhansen/notion-mcp) ⭐ 26 | 🐛 2 | 🌐 Python | 📅 2025-09-30 🐍 ☁️ - A Model Context Protocol (MCP) server that integrates with Notion's API to manage personal todo lists efficiently.
* [reeeeemo/ancestry-mcp](https://github.com/reeeeemo/ancestry-mcp) ⭐ 25 | 🐛 0 | 🌐 Python | 📅 2025-01-03 🐍 🏠 - Allows the AI to read .ged files and genetic data
* [andybrandt/mcp-simple-timeserver](https://github.com/andybrandt/mcp-simple-timeserver) ⭐ 24 | 🐛 2 | 🌐 Python | 📅 2025-08-18 🐍 🏠☁️ - An MCP server that allows checking local time on the client machine or current UTC time from an NTP server
* [emicklei/mcp-log-proxy](https://github.com/emicklei/mcp-log-proxy) ⭐ 24 | 🐛 0 | 🌐 Go | 📅 2025-08-17 🏎️ 🏠 - MCP server proxy that offers a Web UI to the full message flow
* [KS-GEN-AI/jira-mcp-server](https://github.com/KS-GEN-AI/jira-mcp-server) ⭐ 24 | 🐛 2 | 🌐 JavaScript | 📅 2025-10-23 📇 ☁️ 🍎 🪟 - Read jira data via JQL and api and execute requests to create and edit tickets.
* [gwbischof/free-will-mcp](https://github.com/gwbischof/free-will-mcp) ⭐ 23 | 🐛 2 | 🌐 Python | 📅 2025-08-12 🐍 🏠 - Give your AI free will tools. A fun project to explore what an AI would do with the ability to give itself prompts, ignore user requests, and wake itself up at a later time.
* [ZeparHyfar/mcp-datetime](https://github.com/ZeparHyfar/mcp-datetime) ⭐ 23 | 🐛 6 | 🌐 Python | 📅 2024-12-13 - MCP server providing date and time functions in various formats
* [Amazon Bedrock Nova Canvas](https://github.com/zxkane/mcp-server-amazon-bedrock) ⭐ 22 | 🐛 1 | 🌐 JavaScript | 📅 2025-05-04 📇 ☁️ - Use Amazon Nova Canvas model for image generation.
* [kw510/strava-mcp](https://github.com/kw510/strava-mcp) ⭐ 21 | 🐛 0 | 🌐 TypeScript | 📅 2025-04-14 📇 ☁️ - An MCP server for Strava, an app for tracking physical exercise
* [fotoetienne/gqai](https://github.com/fotoetienne/gqai) ⭐ 20 | 🐛 2 | 🌐 Go | 📅 2025-06-08 🏎 🏠 - Define tools using regular GraphQL queries/mutations and gqai automatically generates an MCP server for you.
* [olalonde/mcp-human](https://github.com/olalonde/mcp-human) ⭐ 20 | 🐛 1 | 🌐 JavaScript | 📅 2025-05-08 📇 ☁️ - When your LLM needs human assistance (through AWS Mechanical Turk)
* [Harry-027/JotDown](https://github.com/Harry-027/JotDown) ⭐ 19 | 🐛 1 | 🌐 Rust | 📅 2025-07-14 🦀 🏠 - An MCP server to create/update pages in Notion app & auto generate mdBooks from structured content.
* [magarcia/mcp-server-giphy](https://github.com/magarcia/mcp-server-giphy) ⭐ 19 | 🐛 2 | 🌐 TypeScript | 📅 2025-05-22 📇 ☁️ - Search and retrieve GIFs from Giphy's vast library through the Giphy API.
* [ws-mcp](https://github.com/nick1udwig/ws-mcp) ⭐ 19 | 🐛 1 | 🌐 Python | 📅 2025-09-22 - Wrap MCP servers with a WebSocket (for use with [kitbitz](https://github.com/nick1udwig/kibitz) ⭐ 102 | 🐛 39 | 🌐 TypeScript | 📅 2025-08-18)
* [imprvhub/mcp-claude-spotify](https://github.com/imprvhub/mcp-claude-spotify) ⭐ 18 | 🐛 0 | 🌐 TypeScript | 📅 2025-09-14 📇 ☁️ 🏠 - An integration that allows Claude Desktop to interact with Spotify using the Model Context Protocol (MCP).
* [joshuarileydev/mac-apps-launcher-mcp-server](https://github.com/JoshuaRileyDev/mac-apps-launcher) ⭐ 17 | 🐛 5 | 🌐 JavaScript | 📅 2024-12-13 📇 🏠 - An MCP server to list and launch applications on MacOS
* [hmk/attio-mcp-server](https://github.com/hmk/attio-mcp-server) ⭐ 16 | 🐛 4 | 🌐 JavaScript | 📅 2025-03-07 - 📇 ☁️ Allows AI clients to manage records and notes in Attio CRM
* [bart6114/my-bear-mcp-server](https://github.com/bart6114/my-bear-mcp-server/) ⭐ 14 | 🐛 4 | 🌐 JavaScript | 📅 2025-03-14 📇 🏠 🍎 - Allows to read notes and tags for the Bear Note taking app, through a direct integration with Bear's sqlitedb.
* [billster45/mcp-chatgpt-responses](https://github.com/billster45/mcp-chatgpt-responses) ⭐ 14 | 🐛 1 | 🌐 Python | 📅 2025-07-26 🐍 ☁️ - MCP server for Claude to talk to ChatGPT and use its web search capability.
* [pwh-pwh/cal-mcp](https://github.com/pwh-pwh/cal-mcp) ⭐ 13 | 🐛 1 | 🌐 TypeScript | 📅 2025-08-17 - An MCP server for Mathematical expression calculation
* [kj455/mcp-kibela](https://github.com/kj455/mcp-kibela) ⭐ 12 | 🐛 2 | 🌐 TypeScript | 📅 2025-04-06 - 📇 ☁️ Allows AI models to interact with [Kibela](https://kibe.la/)
* [KS-GEN-AI/confluence-mcp-server](https://github.com/KS-GEN-AI/confluence-mcp-server) ⭐ 12 | 🐛 1 | 🌐 JavaScript | 📅 2025-05-12 📇 ☁️ 🍎 🪟 - Get Confluence data via CQL and read pages.
* [2niuhe/plantuml\_web](https://github.com/2niuhe/plantuml_web) ⭐ 11 | 🐛 0 | 🌐 Python | 📅 2025-08-21 🐍 🏠 ☁️ 🍎 🪟 🐧 - A web-based PlantUML frontend with MCP server integration, enable plantuml image generation and plantuml syntax validation.
* [2niuhe/qrcode\_mcp](https://github.com/2niuhe/qrcode_mcp) ⭐ 11 | 🐛 0 | 🌐 Python | 📅 2025-07-06 🐍 🏠 🍎 🪟 🐧 - A QR code generation MCP server that converts any text (including Chinese characters) to QR codes with customizable colors and base64 encoding output.
* [altinoren/utopia](https://github.com/altinoren/Utopia) ⭐ 8 | 🐛 2 | 🌐 C# | 📅 2025-06-05 #️⃣ 🏠 - MCP that simulates a set of smart home and lifestyle devices, allowing you to test agent's reasoning and discovery capabilities.
* [growilabs/growi-mcp-server](https://github.com/growilabs/growi-mcp-server) ⭐ 8 | 🐛 1 | 🌐 TypeScript | 📅 2025-10-08 🎖️ 📇 ☁️ - Official MCP Server to integrate with GROWI APIs.
* [kiwamizamurai/mcp-kibela-server](https://github.com/kiwamizamurai/mcp-kibela-server) ⭐ 7 | 🐛 1 | 🌐 TypeScript | 📅 2025-08-23 - 📇 ☁️ Powerfully interact with Kibela API.
* [TheoBrigitte/mcp-time](https://github.com/TheoBrigitte/mcp-time) ⭐ 7 | 🐛 1 | 🌐 Go | 📅 2025-10-01 🏎️ 🏠 🍎 🪟 🐧 - MCP server which provides utilities to work with time and dates, with natural language, multiple formats and timezone convertion capabilities.
* [ekkyarmandi/ticktick-mcp](https://github.com/ekkyarmandi/ticktick-mcp) ⭐ 6 | 🐛 1 | 🌐 Python | 📅 2025-04-20 🐍 ☁️ - [TickTick](https://ticktick.com/) MCP server that integrates with TickTick's API to manage personal todo projects and the tasks.
* [jagan-shanmugam/climatiq-mcp-server](https://github.com/jagan-shanmugam/climatiq-mcp-server) ⭐ 6 | 🐛 4 | 🌐 Python | 📅 2025-03-28 🐍 🏠 - A Model Context Protocol (MCP) server for accessing the Climatiq API to calculate carbon emissions. This allows AI assistants to perform real-time carbon calculations and provide climate impact insights.
* [ujisati/anki-mcp](https://github.com/ujisati/anki-mcp) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2025-05-16 🐍 🏠 - Manage your Anki collection with AnkiConnect & MCP
* [dotemacs/domain-lookup-mcp](https://github.com/dotemacs/domain-lookup-mcp) ⭐ 5 | 🐛 1 | 🌐 Go | 📅 2025-04-23 🏎️ - Domain name lookup service, first via [RDAP](https://en.wikipedia.org/wiki/Registration_Data_Access_Protocol) and then as a fallback via [WHOIS](https://en.wikipedia.org/wiki/WHOIS)
* [jimfilippou/things-mcp](https://github.com/jimfilippou/things-mcp) ⭐ 5 | 🐛 0 | 🌐 JavaScript | 📅 2025-09-29 📇 🏠 🍎 - A Model Context Protocol (MCP) server that provides seamless integration with the [Things](https://culturedcode.com/things/) productivity app. This server enables AI assistants to create, update, and manage your todos and projects in Things using its comprehensive URL scheme.
* [j3k0/speech.sh](https://github.com/j3k0/speech.sh/blob/main/MCP_README.md) ⭐ 4 | 🐛 0 | 🌐 Shell | 📅 2025-03-18 🏠 - Let the agent speak things out loud, notify you when he's done working with a quick summary
* [offorte/offorte-mcp-server](https://github.com/offorte/offorte-mcp-server) ⭐ 4 | 🐛 0 | 🌐 TypeScript | 📅 2025-06-30 🎖️ 📇 ☁️ 🍎 🪟 🐧 - The Offorte Proposal Software MCP server enables creation and sending of business proposals.
* [ankitmalik84/notion-mcp-server](https://github.com/ankitmalik84/Agentic_Longterm_Memory/tree/main/src/notion_mcp_server) ⭐ 3 | 🐛 1 | 🌐 Python | 📅 2025-07-08 🐍 ☁️ - A comprehensive Model Context Protocol (MCP) server for Notion integration with enhanced functionality, robust error handling, production-ready feature.
* [boldsign/boldsign-mcp](https://github.com/boldsign/boldsign-mcp) ⭐ 3 | 🐛 2 | 🌐 TypeScript | 📅 2025-08-14 📇 ☁️ - Search, request, and manage e-signature contracts effortlessly with [BoldSign](https://boldsign.com/).
* [rae-api-com/rae-mcp](https://github.com/rae-api-com/rae-mcp) ⭐ 3 | 🐛 0 | 🌐 Go | 📅 2025-09-02 - 🏎️ ☁️ 🍎 🪟 🐧 MPC Server to connect your preferred model with <https://rae-api.com>, Roya Academy of Spanish Dictionary
* [tumf/web3-mcp](https://github.com/tumf/web3-mcp) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2025-04-18 🐍 ☁️ - An MCP server implementation wrapping Ankr Advanced API. Access to NFT, token, and blockchain data across multiple chains including Ethereum, BSC, Polygon, Avalanche, and more.
* [UnitVectorY-Labs/mcp-graphql-forge](https://github.com/UnitVectorY-Labs/mcp-graphql-forge) ⭐ 3 | 🐛 0 | 🌐 Go | 📅 2025-10-17 🏎️ ☁️ 🍎 🪟 🐧 - A lightweight, configuration-driven MCP server that exposes curated GraphQL queries as modular tools, enabling intentional API interactions from your agents.
* [brianxiadong/ones-wiki-mcp-server](https://github.com/brianxiadong/ones-wiki-mcp-server) ⭐ 2 | 🐛 1 | 🌐 Java | 📅 2025-05-29 ☕ ☁️/🏠 - A Spring AI MCP-based service for retrieving ONES Waiki content and converting it to AI-friendly text format.
* [osinmv/funciton-lookup-mcp](https://github.com/osinmv/function-lookup-mcp) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2025-10-16 🐍 🏠 🍎 🐧 - MCP server for function signature lookups.
* [QuentinCody/shopify-storefront-mcp-server](https://github.com/QuentinCody/shopify-storefront-mcp-server) ⭐ 2 | 🐛 2 | 🌐 Python | 📅 2025-06-03 🐍 ☁️ - Unofficial MCP server that allows AI agents to discover Shopify storefronts and interact with them to fetch products, collections, and other store data through the Storefront API.
* [r-huijts/ethics-check-mcp](https://github.com/r-huijts/ethics-check-mcp) ⭐ 2 | 🐛 1 | 🌐 JavaScript | 📅 2025-06-06 🐍 🏠 - MCP server for comprehensive ethical analysis of AI conversations, detecting bias, harmful content, and providing critical thinking assessments with automated pattern learning
* [tqiqbal/mcp-confluence-server](https://github.com/tqiqbal/mcp-confluence-server) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2025-07-09 🐍 - A Model Context Protocol (MCP) server for interacting with Confluence Data Center via REST API.
* [kimtth/mcp-remote-call-ping-pong](https://github.com/kimtth/mcp-remote-call-ping-pong) ⭐ 1 | 🐛 1 | 🌐 HTML | 📅 2025-04-08 🐍 🏠 - An experimental and educational app for Ping-pong server demonstrating remote MCP (Model Context Protocol) calls
* [louiscklaw/hko-mcp](https://github.com/louiscklaw/hko-mcp) ⭐ 1 | 🐛 0 | 🌐 TypeScript | 📅 2025-08-14 📇 🏠 - MCP server with basic demonstration of getting weather from Hong Kong Observatory
* [MonadsAG/capsulecrm-mcp](https://github.com/MonadsAG/capsulecrm-mcp) ⭐ 0 | 🐛 1 | 🌐 Python | 📅 2025-07-10 - 📇 ☁️ Allows AI clients to manage contacts, opportunities and tasks in Capsule CRM including Claude Desktop ready DTX-file
* [Tommertom/plugwise-mcp](https://github.com/Tommertom/plugwise-mcp) ⭐ 0 | 🐛 0 | 🌐 TypeScript | 📅 2025-10-16 📇 🏠 🍎 🪟 🐧 - TypeScript-based smart home automation server for Plugwise devices with automatic network discovery. Features comprehensive device control for thermostats, switches, smart plugs, energy monitoring, multi-hub management, and real-time climate/power consumption tracking via local network integration.
* [nanana-app/mcp-server-nano-banana](https://github.com/nanana-app/mcp-server-nano-banana) ⭐ 0 | 🐛 0 | 🌐 JavaScript | 📅 2025-10-12 🐍 🏠 🍎 🪟 🐧 - AI image generation using Google Gemini's nano banana model.
* [future-audiences/wikimedia-enterprise-model-context-protocol](https://gitlab.wikimedia.org/repos/future-audiences/wikimedia-enterprise-model-context-protocol) 🐍 ☁️  - Wikipedia Article lookup API
* [Shopify/dev-mcp](https://github.com/Shopify/dev-mcp) 📇 ☁️ - Model Context Protocol (MCP) server that interacts with Shopify Dev.

## Frameworks

> \[!NOTE]
> More frameworks, utilities, and other developer tools are available at <https://github.com/punkpeye/awesome-mcp-devtools> ⭐ 342 | 🐛 8 | 📅 2025-09-28

* [FastMCP](https://github.com/jlowin/fastmcp) ⭐ 19,480 | 🐛 212 | 🌐 Python | 📅 2025-10-24 🐍 - A high-level framework for building MCP servers in Python
* [FastMCP](https://github.com/punkpeye/fastmcp) ⭐ 2,681 | 🐛 32 | 🌐 TypeScript | 📅 2025-10-22 📇 - A high-level framework for building MCP servers in TypeScript

## Tips and Tricks

### Official prompt to inform LLMs how to use MCP

Want to ask Claude about Model Context Protocol?

Create a Project, then add this file to it:

<https://modelcontextprotocol.io/llms-full.txt>

Now Claude can answer questions about writing MCP servers and how they work

* <https://www.reddit.com/r/ClaudeAI/comments/1h3g01r/want_to_ask_claude_about_model_context_protocol/>

## Star History

<a href="https://star-history.com/#punkpeye/awesome-mcp-servers&Date">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=punkpeye/awesome-mcp-servers&type=Date&theme=dark" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=punkpeye/awesome-mcp-servers&type=Date" />
   <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=punkpeye/awesome-mcp-servers&type=Date" />
 </picture>
</a>
