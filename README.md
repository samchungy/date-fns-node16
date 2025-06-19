1. Run

```
pnpm install
```

2. Build

```
pnpm build
```

3. See error

```bash
> debug-zod4@1.0.0 build /Users/samc/me/debug-zod4
> tsc

node_modules/.pnpm/date-fns@4.1.0/node_modules/date-fns/addDays.d.cts:1:46 - error TS1541: Type-only import of an ECMAScript module from a CommonJS module must have a 'resolution-mode' attribute.

1 import type { ContextOptions, DateArg } from "./types.js";
                                               ~~~~~~~~~~~~


Found 1 error in node_modules/.pnpm/date-fns@4.1.0/node_modules/date-fns/addDays.d.cts:1

node_modules/.pnpm/date-fns@4.1.0/node_modules/date-fns/addDays.d.cts:1:46 - error TS1541: Type-only import of an ECMAScript module from a CommonJS module must have a 'resolution-mode' attribute.

1 import type { ContextOptions, DateArg } from "./types.js";
```
