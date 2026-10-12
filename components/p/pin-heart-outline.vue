<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pgb9l1boi"/><path class="y8d792rqj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pin-heart-outline" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pgb9l1boi {
  d: path("M12 21.25C8 17.75 5 14 5 10a7 7 0 0 1 14 0c0 4-3 7.75-7 11.25");
}

.y8d792rqj {
  d: path("M12 13.25c-2.25-1.5-3.25-2.6-3.25-3.85A1.63 1.63 0 0 1 12 8.8a1.63 1.63 0 0 1 3.25.6c0 1.25-1 2.35-3.25 3.85");
}

</style>
