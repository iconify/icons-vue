<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mxy1-qb_k"/><path class="ocu24bbzy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:rent-increase" /></template>
<style>
.mxy1-qb_k {
  d: path("M12.6 19H2.5V7.5h17v4.2");
}

.ocu24bbzy {
  d: path("M5 7.5V5h16.5v9.1M5 16.5h.01M17 10h.01M6.25 13.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm3.5 0H15m-2.25 0v2m2.25-2v.3m3 8.2V14.5m-3 3l3-3l3 3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
