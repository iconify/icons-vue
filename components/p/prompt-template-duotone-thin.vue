<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z92okmbgh"/><path class="i4enr0m-s"/><path class="jrpnc2pnl"/><path class="r182r524c"/><path class="wz1gh1b4o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:prompt-template-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i4enr0m-s {
  fill: currentColor;
  d: path("M7 15.5A2.5 2.5 0 0 1 9.5 13h5a2.5 2.5 0 0 1 2.5 2.5 2.5 2.5 0 0 1 -2.5 2.5h-5A2.5 2.5 0 0 1 7 15.5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.jrpnc2pnl {
  d: path("M15 5h3a3 3 0 0 1 3 3v10a3 3 0 0 1 -3 3H6a3 3 0 0 1 -3 -3V8a3 3 0 0 1 3 -3h3");
}

.r182r524c {
  d: path("M7 9h10");
}

.wz1gh1b4o {
  d: path("M7 15.5A2.5 2.5 0 0 1 9.5 13h5a2.5 2.5 0 0 1 2.5 2.5 2.5 2.5 0 0 1 -2.5 2.5h-5A2.5 2.5 0 0 1 7 15.5");
}

.z92okmbgh {
  fill: currentColor;
  d: path("M15 5h3a3 3 0 0 1 3 3v10a3 3 0 0 1 -3 3H6a3 3 0 0 1 -3 -3V8a3 3 0 0 1 3 -3h3");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
