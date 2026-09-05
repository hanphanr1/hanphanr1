<div align="center">

<sub>BEHIND EVERY CLEAN OUTPUT IS A SYSTEM THAT HANDLED THE MESS.</sub>

# T P T T H

**AUTOMATION TOOLING · CHECKER SYSTEMS · PROXY WORKFLOWS**

`hanphanr1` &nbsp; // &nbsp; Python first. Terminal driven.

<br>

### I don't just send requests.<br>I build what happens before, between, and after them.

<br>

<img alt="Python" src="https://img.shields.io/badge/PYTHON-0d1117?style=for-the-badge&logo=python&logoColor=58a6ff">
<img alt="HTTP and sessions" src="https://img.shields.io/badge/HTTP_%2F_SESSIONS-0d1117?style=for-the-badge&logoColor=58a6ff">
<img alt="Concurrency" src="https://img.shields.io/badge/CONCURRENCY-0d1117?style=for-the-badge&logoColor=58a6ff">
<img alt="Telegram bots" src="https://img.shields.io/badge/TELEGRAM_BOTS-0d1117?style=for-the-badge&logo=telegram&logoColor=58a6ff">

</div>

<br>

```text
┌─ tptth@workbench
│
├── core       Python / HTTP / sessions / concurrency
├── tooling    service checkers / proxy utilities / task bots
├── processing OCR / parsing / filtering / deduplication
└── output     classified results, not a wall of raw responses
```

## `01 / THE WORK`

**Give me a repetitive workflow. I'll turn it into a tool.**

I build Python-based service checkers and automation utilities around the parts that make a job more than a single request: **session state, proxy selection, response interpretation, worker coordination, retries, and usable output**.

The work spans **subscription services, AI tools, CAPTCHA providers, proxy platforms, and infrastructure accounts**. Different services, different response formats, different edge cases—the same need to turn noisy inputs into understandable results.

My focus isn't a page someone clicks through. It's the tooling doing the work underneath.

## `02 / WHAT I BUILD`

### `>` Service checkers that read beyond the status code

- Handle cookie-backed sessions and API-key validation in service-specific workflows.
- Parse account state, subscription details, plan labels, and available infrastructure metadata.
- Classify responses and export categorized results instead of treating every HTTP `200` as success.

### `>` Proxy-aware execution

- Integrate proxy pools into request workflows.
- Retrieve paginated proxy inventories from providers and export them into usable formats.
- Combine session handling, retries, and request pacing around service-specific behavior.

### `>` Workers, queues, and batch pipelines

- Use `ThreadPoolExecutor` for concurrent checking tasks and `asyncio` for asynchronous workflows.
- Coordinate queued jobs, process batches, and surface execution progress.
- Filter and deduplicate text data before it becomes downstream noise.

### `>` CAPTCHA & image-processing tooling

- Work with CAPTCHA-service integrations and API-key checks.
- Connect OCR and image-processing components using `ddddocr`, `Pillow`, and `onnxruntime`.
- Integrate solver pools into automated task flows.

### `>` Telegram-operated utilities

- Build bot workflows with `Telethon`, event handlers, and job queues.
- Connect chat commands to processing tasks rather than stopping at canned replies.
- Run text-processing and deduplication utilities behind a conversational control interface.

## `03 / INSIDE THE TOOLCHAIN`

| Layer | Tools & mechanisms |
| :--- | :--- |
| **Primary language** | Python |
| **HTTP clients** | `requests` · `curl_cffi` |
| **Concurrent execution** | `ThreadPoolExecutor` · `threading` · `asyncio` |
| **Bot control** | `Telethon` · event handlers · queued jobs |
| **Image processing** | `Pillow` · `onnxruntime` · `ddddocr` |
| **Supporting runtime** | Node.js · HTTP/HTTPS modules · proxy agents |
| **CLI & output** | `argparse` · `colorama` · progress reporting · categorized exports |

## `04 / THE PART THAT MATTERS`

**Sending a request is the easy part. Knowing what happened is the work.**

A response can be successful at the transport layer and still be useless to the task. A batch can finish and still leave unreadable output. More workers can mean more noise—not better execution.

That's where I put the attention:

```text
SESSION STATE       before the request
PROXY HANDLING      around the connection
RESPONSE PARSING    beyond the status code
RETRY & PACING      between attempts
CLASSIFICATION      before the export
READABLE OUTPUT     at the end of the run
```

> Not just “does it run?” — “can I tell what it actually did?”

## `05 / OPERATING PRINCIPLES`

```text
01   Understand the workflow before automating it.
02   Parse the evidence. Don't guess from a status code.
03   Make failures visible before adding more workers.
04   Keep the output useful, not just verbose.
05   Automate repetition. Keep judgment human.
```

<br>

<div align="center">

<a href="https://github.com/hanphanr1?tab=repositories"><img alt="Explore public repositories" src="https://img.shields.io/badge/READ_THE_SOURCE-0d1117?style=for-the-badge&logo=github&logoColor=58a6ff"></a>

<br><br>

---

**Quiet terminal. Heavy lifting.**

<sub>TPTTH &nbsp; // &nbsp; <a href="https://github.com/hanphanr1">@hanphanr1</a></sub>

</div>
