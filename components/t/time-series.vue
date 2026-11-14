<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j_q_y1bdx"/><path class="sx_tj-kzj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:time-series" /></template>
<style>
.j_q_y1bdx {
  d: path("M3.5 3.5v17h17");
}

.sx_tj-kzj {
  d: path("m6.5 15.5l3.5-5l3.5 3.5L17 8M8 20.5v-2m4.5 2v-2m4.5 2v-2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
