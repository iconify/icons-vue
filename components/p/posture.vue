<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="muq3dfb7h"/><path class="mw7evd5pv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:posture" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.muq3dfb7h {
  cx: 9px;
  cy: 5px;
  r: 2.25px;
}

.mw7evd5pv {
  d: path("M6.25 21.25V13.5a2.75 2.75 0 0 1 5.5 0v7.75Zm10-18.5v2.5m0 3v2.5m0 3v2.5m0 3v2");
}

</style>
