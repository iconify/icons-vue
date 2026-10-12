<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tphd_i96b"/><circle class="v0gbo5fpj"/><circle class="rslbrvbax"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:skateboard-ramp" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rslbrvbax {
  cx: 17px;
  cy: 18.75px;
  r: 2.25px;
}

.tphd_i96b {
  d: path("M2.75 10.5A1.5 1.5 0 0 1 4.25 9h.5c.8 0 1.4.75 2 1.25h10.5c.6-.5 1.2-1.25 2-1.25h.5a1.5 1.5 0 0 1 1.5 1.5c0 1.75-1.5 3.25-3.25 3.25H6a3.25 3.25 0 0 1-3.25-3.25");
}

.v0gbo5fpj {
  cx: 7px;
  cy: 18.75px;
  r: 2.25px;
}

</style>
