<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="mfsve_32m"/><path class="q04h27byz"/><path class="r49h5hxcs"/><path class="qy4y3cbmh"/><path class="dvgqqgmhk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:travel-money-outline-bold" /></template>
<style>
.dvgqqgmhk {
  d: path("M12 11.5v4");
}

.mfsve_32m {
  d: path("M2 10a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v7a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.q04h27byz {
  d: path("M5.5 11.5v4");
}

.qy4y3cbmh {
  d: path("M9 13.5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.r49h5hxcs {
  d: path("M18.5 11.5v4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
