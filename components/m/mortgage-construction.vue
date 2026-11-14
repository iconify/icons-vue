<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xlu18bclm"/><path class="km2gdsldf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mortgage-construction" /></template>
<style>
.km2gdsldf {
  d: path("M16 7V4h2v4.75m-3 11a3 3 0 0 1 6 0m-6.75.25h7.5M18 16.75v1.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xlu18bclm {
  d: path("M11.46 20.5H4v-10l8-7l8 7v3.44");
}

</style>
