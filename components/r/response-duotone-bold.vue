<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ak588yg4c"/><path class="pmhsn037r"/><path class="lezu57blc"/><path class="xbzn4ib3y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:response-duotone-bold" /></template>
<style>
.ak588yg4c {
  fill: currentColor;
  d: path("M15 6a2 2 0 0 1 2 -2h3a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2h-3a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.lezu57blc {
  d: path("M2 12h13");
}

.pmhsn037r {
  d: path("M15 6a2 2 0 0 1 2 -2h3a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2h-3a2 2 0 0 1 -2 -2Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.xbzn4ib3y {
  d: path("m5 9 -3 3 3 3");
}

</style>
