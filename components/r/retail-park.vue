<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ppxzn_yyj"/><path class="bcsiu_mfd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:retail-park" /></template>
<style>
.bcsiu_mfd {
  d: path("M9.5 13V9h5v4M6 5.75h12M2.5 21.5h19m-19-5v5m6.25-5v5m6.5-5v5m6.25-5v5");
}

.ppxzn_yyj {
  d: path("M2.5 2.5h19V13h-19Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
