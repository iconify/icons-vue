<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="s-06yxs4b"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:sonic-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.s-06yxs4b {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.631 13.94h.002zm-.001.001c-3.023.907-5.523 2.23-7.089 3.78l-.069.07c.417.393.873.745 1.367 1.044l.106-.13a20 20 0 0 1 5.685-4.764m.35-1.344H4c.12 1.617.722 3.1 1.666 4.307l.043-.044c.97-.955 2.231-1.823 3.753-2.58c1.334-.664 2.866-1.234 4.518-1.683m-3.826-6.648a18.6 18.6 0 0 0 9.845 5.149C19.549 7.105 16.147 4 12.014 4a8.1 8.1 0 0 0-3.082.61c.386.464.798.915 1.222 1.339m-3.613.329c1.566 1.553 4.067 2.874 7.091 3.783a20 20 0 0 1-4.326-3.266a20 20 0 0 1-1.363-1.5l-.106-.13a8 8 0 0 0-1.364 1.044zm3.613 11.772a19 19 0 0 0-1.222 1.34a8 8 0 0 0 3.082.61c4.133 0 7.535-3.106 7.986-7.1a18.6 18.6 0 0 0-9.845 5.15zM9.46 9.718c-1.52-.757-2.782-1.626-3.751-2.58l-.043-.043A7.93 7.93 0 0 0 4 11.403h9.978c-1.651-.45-3.182-1.02-4.518-1.685");
}

</style>
