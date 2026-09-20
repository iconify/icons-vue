<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="n_4qdqi8k"/><path class="agonkhobo"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mta-background" /></template>
<style>
.agonkhobo {
  fill: var(--svg-color--fff, #fff);
  d: path("M6.5 5H4v10h3V9.219C6.995 8.496 6.985 7 8.75 7c1.632 0 1.75 1.487 1.75 2.255V15h3v-4.867C13.5 8.668 13.5 7 15.25 7C16.782 7 17 8.255 17 9.318V15h2.997V9.388c.003-.85.006-1.958-.498-2.773C19.279 6.222 18.529 5 16.5 5c-1.035 0-2.477.157-3.308 1.752C12.997 6.28 12.308 5 10 5c-1.921 0-2.621.971-2.956 1.436L7 6.498zM20 16.5H4V19h16z");
}

.ft5dv1b6b {
  fill: none;
}

.n_4qdqi8k {
  fill: var(--svg-color--ffb634, #ffb634);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
