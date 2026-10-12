<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="xh4evtb-j"/><path class="x9i9b9bhm"/><circle class="u5pl82bll"/><path class="kz85adcdz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sleep" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kz85adcdz {
  d: path("M16 2.75h4l-4 4h4");
}

.u5pl82bll {
  cx: 10.5px;
  cy: 17px;
  r: 1px;
}

.x9i9b9bhm {
  d: path("M7 12.75c.65.55 1.6.55 2.25 0m2.5 0c.65.55 1.6.55 2.25 0");
}

.xh4evtb-j {
  cx: 10.5px;
  cy: 13.5px;
  r: 7.75px;
}

</style>
