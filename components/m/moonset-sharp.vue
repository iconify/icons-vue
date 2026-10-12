<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="lb9w9mc_w"/><path class="dbfrcacjm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:moonset-sharp" /></template>
<style>
.dbfrcacjm {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19.5 8h.01");
}

.lb9w9mc_w {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 18h18M9.67 18a4 4 0 0 1 1.94-7.23a3.25 3.25 0 0 0 4.37 4.37A4 4 0 0 1 14.33 18ZM12 3.5v4.25M9.75 5.5L12 7.75l2.25-2.25");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
