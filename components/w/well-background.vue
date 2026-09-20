<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="ru4s7he_y"/><path class="ck6tx00ct"/><path class="t3ysc1alq"/><path class="n2h8f-q8b"/><path class="bjfnotxss"/><path class="lz16l6bcd"/><path class="j_h9a91ms"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:well-background" /></template>
<style>
.bjfnotxss {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.459 15.442c.155.37.28.91.325 1.135c.204-1.385 1.374-4.354 4.409-5.159c.005-.8-.075-2.6-.425-3.459c-3.954 1.805-4.52 5.739-4.31 7.483");
}

.ck6tx00ct {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.668 17.877A7.208 7.208 0 0 0 13.408 4A8.067 8.067 0 1 1 4 13.408a7.21 7.21 0 0 0 6.668 4.469");
}

.ft5dv1b6b {
  fill: none;
}

.j_h9a91ms {
  fill: var(--svg-color--fff, #fff);
  d: path("M8.974 9.078a9.2 9.2 0 0 1 1.83 2.484c.27-.555 1.009-1.834 1.799-2.484c-.245-.635-.94-2.11-1.8-2.934c-.885.814-1.59 2.299-1.83 2.934");
}

.lz16l6bcd {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.113 14.623c-1.15-2.284-2.96-3.094-3.719-3.21c-.035-.634-.01-2.209.39-3.438c2.474 1.16 3.58 3.129 3.82 3.974a7.8 7.8 0 0 0-.49 2.674");
}

.n2h8f-q8b {
  fill: var(--svg-color--fff, #fff);
  d: path("M4.27 11.437c.23 1.79 1.81 5.45 6.309 5.754c-.885-5.234-4.574-6.018-6.308-5.754m13.011 0c-.225 1.79-1.81 5.45-6.308 5.754c.89-5.234 4.579-6.018 6.308-5.754");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.ru4s7he_y {
  fill: var(--svg-color--ffce6c, #ffce6c);
  d: path("M24 0H0v24h24z");
}

.t3ysc1alq {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.876 10.669A7.209 7.209 0 0 1 6.46 16.518a7.207 7.207 0 1 0 9.763-10.443a7.18 7.18 0 0 1 1.65 4.599z");
}

</style>
