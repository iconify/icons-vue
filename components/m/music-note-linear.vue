<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="lvnegepox"/><path class="n6e0xbyjd"/><path class="so9syjbwr"/><path class="eek4bo4aq"/><path class="xkfhx0hpx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:music-note-linear" /></template>
<style>
.eek4bo4aq {
  d: path("M21 17V6");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lvnegepox {
  d: path("M9 19C9 20.6569 7.65685 22 6 22C4.34315 22 3 20.6569 3 19C3 17.3431 4.34315 16 6 16C7.65685 16 9 17.3431 9 19Z");
}

.n6e0xbyjd {
  d: path("M21 17C21 18.6569 19.6569 20 18 20C16.3431 20 15 18.6569 15 17C15 15.3431 16.3431 14 18 14C19.6569 14 21 15.3431 21 17Z");
}

.so9syjbwr {
  d: path("M9 19V8");
}

.xkfhx0hpx {
  d: path("M11.7351 5.08836L15.7351 3.75503C18.1376 2.95419 19.3388 2.55378 20.1694 3.15242C21 3.75107 21 5.0173 21 7.54976V8.00006L9 12.0001V8.88309C9 7.49165 9 6.79593 9.37752 6.27215C9.75503 5.74838 10.4151 5.52837 11.7351 5.08836Z");
}

</style>
