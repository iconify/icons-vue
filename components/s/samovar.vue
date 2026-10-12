<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="teyr3bc3j"/><path class="uj718v1jd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:samovar" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.teyr3bc3j {
  d: path("M9.25 8.25C9.25 6.6 10.5 5.5 12 5.5s2.75 1.1 2.75 2.75ZM12 5.5V3M8 8.25h8c1.5 0 2.5 1.25 2.5 2.75c0 3-2 5.5-4 6.5l1.75 2.5a.75.75 0 0 1-.6 1.25h-7.3a.75.75 0 0 1-.6-1.25l1.75-2.5c-2-1-4-3.5-4-6.5c0-1.5 1-2.75 2.5-2.75");
}

.uj718v1jd {
  d: path("M18.25 13.5H20v1.75m-12.75-4c3 .75 6.5.75 9.5 0");
}

</style>
