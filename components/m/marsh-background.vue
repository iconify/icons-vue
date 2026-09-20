<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="h224pzbef"/><path class="k0aj0pawj"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:marsh-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.h224pzbef {
  fill: var(--svg-color--34d399, #34d399);
  d: path("M24 0H0v24h24z");
}

.k0aj0pawj {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.5 9.45L8 8.57v4.93c0 1.935 1.79 3.5 4 3.5s4-1.565 4-3.5v-7h-5.475l2.585 1.45h1.39v5.55c0 1.1-1.12 2-2.5 2s-2.5-.9-2.5-2zm-3-1.76v6.56c0 2.35 2.46 4.25 5.5 4.25s5.5-1.9 5.5-4.25V5.5H8.74L6.06 4H19v10c0 3.315-3.135 6-7 6s-7-2.685-7-6V6.81z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
