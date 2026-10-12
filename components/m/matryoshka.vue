<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u1tsijb-q"/><circle class="no-xaab-v"/><path class="syh5518jg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:matryoshka" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.no-xaab-v {
  cx: 12px;
  cy: 6.5px;
  r: 1.25px;
}

.syh5518jg {
  d: path("M8.5 13.5c2 1.25 5 1.25 7 0M12 16.25v2.5");
}

.u1tsijb-q {
  d: path("M12 2.75A3.75 3.75 0 0 0 8.25 6.5c0 .9.3 1.6.8 2.2c-2.05 1.3-3.3 3.8-3.3 6.8c0 3.5 2 5.75 6.25 5.75s6.25-2.25 6.25-5.75c0-3-1.25-5.5-3.3-6.8c.5-.6.8-1.3.8-2.2A3.75 3.75 0 0 0 12 2.75");
}

</style>
