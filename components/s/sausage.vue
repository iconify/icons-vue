<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nejhvrk6q"/><path class="gq5zktbyq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sausage" /></template>
<style>
.gq5zktbyq {
  d: path("M9.61 14A12 12 0 0 1 14 9.61");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nejhvrk6q {
  d: path("M5.51 16.12A15 15 0 0 1 16.12 5.51a3 3 0 0 1 1.55 5.8a9 9 0 0 0-6.36 6.36a3 3 0 0 1-5.8-1.55");
}

</style>
