<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zhynylfsx"/><path class="ty0psfbhu"/><path class="plxcz9gig"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mri-scanner" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.plxcz9gig {
  d: path("M3.5 13h17a1 1 0 0 1 1 1a1 1 0 0 1-1 1h-17a1 1 0 0 1-1-1a1 1 0 0 1 1-1M6 15v6.5M18 15v6.5");
}

.ty0psfbhu {
  d: path("M7.5 10.5a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0");
}

.zhynylfsx {
  d: path("M8.25 3h7.5A5.25 5.25 0 0 1 21 8.25v4.5A5.25 5.25 0 0 1 15.75 18h-7.5A5.25 5.25 0 0 1 3 12.75v-4.5A5.25 5.25 0 0 1 8.25 3");
}

</style>
