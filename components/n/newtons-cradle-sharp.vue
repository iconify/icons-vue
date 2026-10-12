<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="y0den0c7g"/><circle class="s_cq4lf5e"/><circle class="xh7m_xblq"/><circle class="s_m417b3y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:newtons-cradle-sharp" /></template>
<style>
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

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xh7m_xblq {
  cx: 13.5px;
  cy: 14.75px;
  r: 1.5px;
}

.y0den0c7g {
  d: path("M2.75 21.25V2.75h18.5v18.5M13.5 2.75v10.5m3-10.5v10.5m-6-10.5L7.66 12.86");
}

</style>
