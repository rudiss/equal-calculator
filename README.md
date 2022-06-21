This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, install dependencies and run the development server:

```bash
yarn && yarn dev
```
Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

The main component is in `components/Calculator/index.tsx`.

Inside `components/Calculator/` we have the following files: `index.tsx`, `styles.ts`, `types.ts`, `utils.ts`. `index.tsx` is the main component, `styles.ts with styledComponents` is the styles file, `types.ts` is the types file, and `utils.ts` is the utility file, also we have a `hook.ts` file witch is a custom hook for the calculator.

To run the test suite, run the following command:
```bash
yarn test
```
Will run the test suite and generate a report in `coverage/lcov.info`.
Open ```coverage/index.html``` to see the report.

Also this project was create with typescript, so you can use the following command to run the type checker:
```bash
yarn tsc
```

**This version number: 5b8d0fd276b6d288905ed2f63a934e057e8feca2**