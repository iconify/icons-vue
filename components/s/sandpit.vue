<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="z4h_u3ymx"/><path class="yhsozrbyk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sandpit" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yhsozrbyk {
  d: path("M5.5 16q3.25-2.5 6.5 0t6.5 0M15 2.5v6m-1.75-6h3.5m-3.5 6h3.5V11L15 12.75L13.25 11Z");
}

.z4h_u3ymx {
  d: path("M2.5 9.5V19a2 2 0 0 0 2 2h15a2 2 0 0 0 2-2V9.5");
}

</style>
