<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lztt4947q"/><path class="j_bxj6hfe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:parking-permit" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j_bxj6hfe {
  d: path("M10 18.5V10h3a2.5 2.5 0 0 1 0 5h-3");
}

.lztt4947q {
  d: path("M8.5 7h7a3.5 3.5 0 0 1 3.5 3.5V18a3.5 3.5 0 0 1-3.5 3.5h-7A3.5 3.5 0 0 1 5 18v-7.5A3.5 3.5 0 0 1 8.5 7M12 7V4.25a1.75 1.75 0 0 1 3.5 0");
}

</style>
