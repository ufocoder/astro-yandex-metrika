# Astro Yandex Metrika

Astro component for Yandex Metrika

## Installation

```bash
npm install astro-yandex-metrika
```

## Usage

```astro
---
import { YandexMetrika } from 'astro-yandex-metrika';

const counterId = import.meta.env.YANDEX_METRIKA_ID;
---

<YandexMetrika id={counterId}/>
```