<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="e6kii_byk"/><path class="zgp77vd-v"/><path class="mhu4k1brd"/><path class="ozoar21sz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:villa-sharp" /></template>
<style>
.e6kii_byk {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 15.45V9h-1l.46-.66l2.58-3.68l.46-.66h8.5l.46.66l2.58 3.68l.46.66h-1v7.25H3.75z");
}

.mhu4k1brd {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.5 12h.01m7.99 0h.01");
}

.ozoar21sz {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.75 20.25l1.15-.9l1.15.9l1.15.9l1.15-.9l1.15-.9l1.15.9l1.15.9l1.15-.9l1.15-.9l1.15.9l1.15.9l1.15-.9l1.15-.9l1.15.9l1.15.9l1.15-.9");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.zgp77vd-v {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 16.25v-4.5h3v4.5");
}

</style>
