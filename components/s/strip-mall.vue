<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lbo_3g28m"/><path class="l7w3msboc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:strip-mall" /></template>
<style>
.l7w3msboc {
  d: path("M5 21.5V16h2.5v5.5m1.75 0V16h2.5v5.5m1.75 0V16H16v5.5m1.75 0V16h2.5M5 12.5h14");
}

.lbo_3g28m {
  d: path("M2.5 6h19v3.5h-19Zm1 3.5v12h17v-12");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
