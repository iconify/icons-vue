<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hcczkwbhd"/><path class="q6hf1pbkj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:spreadsheet-db" /></template>
<style>
.hcczkwbhd {
  d: path("M11.7 15.5H2.5v-13h15v8.2m-15-4.2h15m-7.5 0v9m-7.5-5h15m-3 4.5a3.5 1.5 0 1 0 7 0a3.5 1.5 0 1 0-7 0Z");
}

.q6hf1pbkj {
  d: path("M14.5 15v5a3.5 1.5 0 0 0 7 0v-5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
