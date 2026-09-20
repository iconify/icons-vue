<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="yizy7bcqp"/><path class="e00xj8bii"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ogn-background" /></template>
<style>
.e00xj8bii {
  fill: var(--svg-color--fff, #fff);
  d: path("M5.837 7.969c-1.5 2.97-.65 6.64 0 8.03l2.474-2.5c-.245-.955-.195-2.4.11-3.59c.36-1.425 1.6-2.855 3.51-2.88c1.345-.015 2.29.62 2.5.94l-8.374 8.5c.35.584 1.37 2.06 2.894 2.88c1.435.77 3.645.794 5.06.4a7.07 7.07 0 0 0 4.68-5.13c.74-3.055-.02-5.8-.53-6.65l-2.43 2.475c.165.95.14 3.09-.42 4.44c-.55 1.35-1.69 2.1-3.38 2.1a3.84 3.84 0 0 1-2.365-.985l8.35-8.545c-2-3.39-5.525-3.62-6.8-3.39a7.06 7.06 0 0 0-5.28 3.9z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.yizy7bcqp {
  fill: var(--svg-color--007cff, #007cff);
  d: path("M24 0H0v24h24z");
}

</style>
