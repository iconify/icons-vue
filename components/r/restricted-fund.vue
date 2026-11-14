<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fp007qefq"/><path class="hjdwu7_5d"/><path class="h9ta0kaat"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:restricted-fund" /></template>
<style>
.fp007qefq {
  d: path("M3.5 6a7 2.5 0 1 0 14 0a7 2.5 0 1 0-14 0Z");
}

.h9ta0kaat {
  d: path("M3.5 10.75a7 2.5 0 0 0 14 0M15 17.5h6v4h-6Zm1.5 0v-1a1.5 1.5 0 0 1 3 0v1");
}

.hjdwu7_5d {
  d: path("M3.5 6v9.5q0 .061.008.123q.009.061.026.122t.042.122t.059.121t.075.119t.091.119q.05.058.108.116t.124.115t.139.112t.155.109t.169.107q.088.053.184.104q.095.051.198.1q.102.05.211.097t.224.093t.237.089t.249.084t.26.081q.133.038.271.075t.281.071t.29.065q.148.032.299.061q.152.029.307.055t.314.05t.321.044t.326.038t.331.033t.335.027t.339.021t.341.015t.343.009q.171.003.343.003q.873 0 1.72-.077m5.28-5.681V6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
