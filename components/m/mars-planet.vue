<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l_ykd8b0q"/><circle class="pbit6lbsn"/><circle class="oruds0ork"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mars-planet" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l_ykd8b0q {
  d: path("M4.96 6h14.08A9.25 9.25 0 1 1 4.96 6m0 0h14.08A9.25 9.25 0 0 0 4.96 6");
}

.oruds0ork {
  cx: 15.25px;
  cy: 16px;
  r: 1.5px;
}

.pbit6lbsn {
  cx: 9px;
  cy: 12.5px;
  r: 2px;
}

</style>
