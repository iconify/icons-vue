<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oscmqi7_r"/><path class="z9ittvbis"/><path class="yegul17ht"/><path class="ec5tld62j"/><path class="gju7e2bvn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:tab-overflow-outline-thin" /></template>
<style>
.ec5tld62j {
  d: path("M17 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.gju7e2bvn {
  d: path("M20 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oscmqi7_r {
  d: path("M2 19V9l2 -2h6l2 2v10");
}

.yegul17ht {
  d: path("M14 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.z9ittvbis {
  d: path("M2 19h20");
}

</style>
