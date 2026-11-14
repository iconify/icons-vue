<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lsja6ob9g"/><path class="bnjdu4b-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:poster-stand" /></template>
<style>
.bnjdu4b-s {
  d: path("M12.75 6a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M8.5 13L11 9.5l2 2l1-1l1.5 2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lsja6ob9g {
  d: path("M8.25 2.5h7.5a1.75 1.75 0 0 1 1.75 1.75v9.5a1.75 1.75 0 0 1-1.75 1.75h-7.5a1.75 1.75 0 0 1-1.75-1.75v-9.5A1.75 1.75 0 0 1 8.25 2.5m3.75 13V19m-4.5 2.5a4.5 2.5 0 0 1 9 0Z");
}

</style>
