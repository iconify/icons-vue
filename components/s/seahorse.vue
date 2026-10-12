<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="obq18zjbr"/><path class="l3hn7_b7u"/><path class="c571tqvaq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:seahorse" /></template>
<style>
.c571tqvaq {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11.25 6.25h.01");
}

.l3hn7_b7u {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.5 19.25c-.25 1.25-1.25 2-2.25 2s-1.75-.75-1.75-1.5s.5-1.25 1.25-1.25");
}

.obq18zjbr {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 3.5c1.5-.75 3.5-.5 4.75.75s1.5 3 .75 4.25c2.75.75 4.5 3 4.25 5.75c-.25 2.5-2 4.25-4.75 4.75l-1.25.25V15.5c0-1.75-1-3-2.5-4c-.75-.5-1-1.25-1-2l-3.5 1.25c-.75.25-1.25-.5-.75-1L8.5 6.5c-.25-1.25 0-2.5.5-3m9.25 7l2-.5c.5-.1.8.45.45.8l-1.8 1.8Z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
