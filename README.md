# lumen-layout

## Changes in this fork

- Set available powered feeder counts independently for 8mm, 12mm, 16mm, and
  24mm tape.
- Parts without an available matching powered feeder fall back to strip
  feeders when space allows. 32mm tape continues to use strip feeders only.
- Powered feeder priority and rail capacity are still respected.

## Run locally

- `npx vite build`
- `npx vite preview`

## AI declaration

AI assistance was used to implement and test the changes in this fork.
