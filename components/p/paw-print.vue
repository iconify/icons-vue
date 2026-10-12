<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w850mc-xu"/><circle class="hnv9gbb9i"/><circle class="iq3w1nbpg"/><circle class="dzjafpb3d"/><circle class="io3g52bpb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:paw-print" /></template>
<style>
.dzjafpb3d {
  cx: 15px;
  cy: 5.75px;
  r: 2.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hnv9gbb9i {
  cx: 4.75px;
  cy: 11px;
  r: 2px;
}

.io3g52bpb {
  cx: 19.25px;
  cy: 11px;
  r: 2px;
}

.iq3w1nbpg {
  cx: 9px;
  cy: 5.75px;
  r: 2.25px;
}

.w850mc-xu {
  d: path("M12 12.25c-2.75 0-6 3.5-6 6.25C6 20 7.25 21 8.75 21c1.25 0 2-.5 3.25-.5s2 .5 3.25.5c1.5 0 2.75-1 2.75-2.5c0-2.75-3.25-6.25-6-6.25");
}

</style>
