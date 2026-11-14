<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="knxtrwbwf"/><path class="e91wkhbhy"/><path class="fipq7ybjz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:turntable-product" /></template>
<style>
.e91wkhbhy {
  d: path("M10.75 4h2.5A1.75 1.75 0 0 1 15 5.75v5.5A1.75 1.75 0 0 1 13.25 13h-2.5A1.75 1.75 0 0 1 9 11.25v-5.5A1.75 1.75 0 0 1 10.75 4m-7 14a9.5 4.75 0 0 0 16.5 0");
}

.fipq7ybjz {
  d: path("m18 17.75l2.25.25l-.25 2.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.knxtrwbwf {
  d: path("M9 10.25A9 3 0 0 0 3 13a9 3 0 0 0 18 0a9 3 0 0 0-6-2.75");
}

</style>
