## Prerequisites

1. We have a link that contains a name with underscore in it:

```md
[CODE_OF_CONDUCT.md]()
```

2. After running remark:

```sh
remark --output -- .
```

3. Link name is formatted:

```md
[CODE\_OF\_CONDUCT.md]()
```

diff: https://github.com/muravjev/repro_remark_underscore/compare/0d32000...defd596

## Question

Is it possible to prevent such behavior?

## Reproduction

repo: https://github.com/muravjev/repro_remark_underscore

```sh
git clone https://github.com/muravjev/repro_remark_underscore.git
cd repro_remark_underscore
pnpm install
pnpm repro
```
