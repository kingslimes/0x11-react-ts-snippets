<div align="center">

# 0x11 React TS Snippets

**Modern, fast and comprehensive React + TypeScript snippets for Next.js 14+ (App Router) and React 18+**

![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-007ACC?logo=visual-studio-code&logoColor=white)
![React](https://img.shields.io/badge/React-18+-61dafb?logo=react)
![Next.js](https://img.shields.io/badge/Next.js-14+%20(App%20Router)-000000?logo=next.js)
![TypeScript](https://img.shields.io/badge/TypeScript-5+-3178C6?logo=typescript)

[![VS Marketplace Version](https://img.shields.io/visual-studio-marketplace/v/kingslimes.0x11-react-ts-snippets?label=VS%20Marketplace&logo=visual-studio-code)](https://marketplace.visualstudio.com/items?itemName=kingslimes.0x11-react-ts-snippets)
[![VS Marketplace Downloads](https://img.shields.io/visual-studio-marketplace/d/kingslimes.0x11-react-ts-snippets?color=brightgreen)](https://marketplace.visualstudio.com/items?itemName=kingslimes.0x11-react-ts-snippets)
[![VS Marketplace Rating](https://img.shields.io/visual-studio-marketplace/stars/kingslimes.0x11-react-ts-snippets)](https://marketplace.visualstudio.com/items?itemName=kingslimes.0x11-react-ts-snippets&ssr=false#review-details)
[![License](https://img.shields.io/github/license/kingslimes/0x11-react-ts-snippets?color=blue)](https://github.com/kingslimes/0x11-react-ts-snippets/blob/main/LICENSE)

</div>

> คอลเลกชัน Snippets คุณภาพสูงสำหรับ React + TypeScript และ Next.js App Router
> เร็ว แม่นยำ พิมพ์ดี โดย kingslimes

ติดตั้ง: https://marketplace.visualstudio.com/items?itemName=kingslimes.0x11-react-ts-snippets
GitHub: https://github.com/kingslimes/0x11-react-ts-snippets

## ทำไมต้องใช้ 0x11-react-ts-snippets?

- TypeScript เต็มรูปแบบ
- รองรับ Next.js App Router (Client + Server Component)
- Prefix สั้น เร็ว จำง่าย
- อัปเดตต่อเนื่อง
- เขียนโดยคนไทย เพื่อคนไทยที่รักความเร็ว

## Installation

เปิด VS Code → Ctrl+Shift+X → พิมพ์ '0x11-react-ts-snippets' → Install

หรือกดลิงก์ตรงนี้: https://marketplace.visualstudio.com/items?itemName=kingslimes.0x11-react-ts-snippets

## Snippets ทั้งหมด

| Prefix   | รายละเอียด                                              |
|----------|----------------------------------------------------------|
| rfcp     | React Functional Component + Props (TSX)                 |
| rfc      | React Functional Component (ไม่มี props)                  |
| ncc      | Next.js Client Component ("use client")                  |
| ncs      | Next.js Server Component + params & searchParams         |
| nc       | Next.js Component ทั่วไป                                  |
| us       | useState<Type>(initial)                                  |
| ue       | useEffect                                                |
| urf      | useRef<HTMLElement>(null)                                |
| ucb      | useCallback                                              |
| rmemo    | React.memo component                                     |
| imps     | import { useState } from "react"                         |
| impe     | import { useEffect } from "react"                        |
| impse    | import { useState, useEffect } from "react"              |
| impr     | import { useRef } from "react"                           |
| impb     | import { useCallback } from "react"                      |
| impm     | import { memo } from "react"                             |
| expr     | export const revalidate = 60                             |
| expd     | export const dynamic = 'auto'                            |
| expf     | export const fetchCache = 'auto'                         |

## ตัวอย่างการใช้งาน

พิมพ์ prefix แล้วกด Tab
```ts
// พิมพ์ ncc + Tab
"use client";

type HomeProps = {}

export default function HomeComponent({}: HomeProps) {
  return (
    <div>Hello from Client Component!</div>
  );
};

// พิมพ์ rfcp + Tab
type ProfileCardProps = {
  name: string
}

export default function ProfileCard({}: ProfileCardProps) {
  return (
    <div>ProfileCard</div>
  );
}
```

## Contributing

ยินดีรับ snippet ใหม่และแก้บั๊กเสมอครับ
เปิด Issue / PR ได้ที่: https://github.com/kingslimes/0x11-react-ts-snippets

## License

MIT License © 2025 kingslimes

ถ้าชอบ ฝากกด Star ที่ GitHub หน่อยนะครับ ขอบคุณมาก!
https://github.com/kingslimes/0x11-react-ts-snippets

Happy coding ครับ!
