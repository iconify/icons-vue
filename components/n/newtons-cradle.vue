<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dmf24hbrz"/><circle class="s_cq4lf5e"/><circle class="xh7m_xblq"/><circle class="s_m417b3y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:newtons-cradle" /></template>
<style>
.dmf24hbrz {
  d: path("M2.75 21.25v-17a1.5 1.5 0 0 1 1.5-1.5h15.5a1.5 1.5 0 0 1 1.5 1.5v17M13.5 2.75v10.5m3-10.5v10.5m-6-10.5L7.66 12.86");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s_cq4lf5e {
  cx: 7.25px;
  cy: 14.3px;
  r: 1.5px;
}

.s_m417b3y {
  cx: 16.5px;
  cy: 14.75px;
  r: 1.5px;
}

.xh7m_xblq {
  cx: 13.5px;
  cy: 14.75px;
  r: 1.5px;
}

</style>
