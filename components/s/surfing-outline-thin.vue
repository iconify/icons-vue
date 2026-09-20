<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f3mcq1ban"/><path class="pynu7yt3k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:surfing-outline-thin" /></template>
<style>
.f3mcq1ban {
  d: path("M12 3c3 3 4 8 3 12H9c-1 -4 0 -9 3 -12");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pynu7yt3k {
  d: path("M3 19c3 -2 6 2 9 0s6 2 9 0");
}

</style>
