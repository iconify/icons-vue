<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kebju1mox"/><path class="bvxdzib4d"/><path class="a9-k66bcy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mri-scan-image" /></template>
<style>
.a9-k66bcy {
  d: path("M9.75 7.75c-1.25 1 .25 2.5-1 3.75S9 14.25 8.5 16m5.75-8.25c1.25 1-.25 2.5 1 3.75s-.25 2.75.25 4.5");
}

.bvxdzib4d {
  d: path("M6.5 12a5.5 6.75 0 1 0 11 0a5.5 6.75 0 1 0-11 0M12 5.25v13.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kebju1mox {
  d: path("M7.375 3h9.25A4.375 4.375 0 0 1 21 7.375v9.25A4.375 4.375 0 0 1 16.625 21h-9.25A4.375 4.375 0 0 1 3 16.625v-9.25A4.375 4.375 0 0 1 7.375 3");
}

</style>
