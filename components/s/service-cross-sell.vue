<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ekf2s55jf"/><path class="zfz2mab_m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:service-cross-sell" /></template>
<style>
.ekf2s55jf {
  d: path("M2.5 15H6l4 2.5h4.25a1.25 1.25 0 0 1 0 2.5H9.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zfz2mab_m {
  d: path("M2.5 21.5H13l7.25-4.75c1-.75.25-2.25-1-1.75l-3.75 2.5m-9-12h11A1.5 1.5 0 0 1 19 7a1.5 1.5 0 0 1-1.5 1.5h-11A1.5 1.5 0 0 1 5 7a1.5 1.5 0 0 1 1.5-1.5m1 3h9A1.5 1.5 0 0 1 18 10v1a1.5 1.5 0 0 1-1.5 1.5h-9A1.5 1.5 0 0 1 6 11v-1a1.5 1.5 0 0 1 1.5-1.5m4.5-3v7m0-7C10.5 3 8 2.25 8 3.75c0 1 2 1.75 4 1.75m0 0c1.5-2.5 4-3.25 4-1.75c0 1-2 1.75-4 1.75");
}

</style>
