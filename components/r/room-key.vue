<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="njt_sfbnu"/><path class="iman5s0zj"/><path class="x99anl3uw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:room-key" /></template>
<style>
.iman5s0zj {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14.5 7h.01");
}

.njt_sfbnu {
  cx: 14.5px;
  cy: 7px;
  r: 4.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x99anl3uw {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.5 11.25v10m0-4.5h2.75m-2.75 3h2.25m-5.5-10l-2.75 2.5m-.82.23l2.14 2.29q.68.73 0 1.46l-2.14 2.29q-.68.73-1.36 0l-2.14-2.29q-.68-.73 0-1.46l2.14-2.29q.68-.73 1.36 0");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
