<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z92okmbgh"/><path class="k5avrj3uw"/><path class="jrpnc2pnl"/><path class="i37wtfbmi"/><path class="n1c_-nuwx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:newsletter-signup-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i37wtfbmi {
  d: path("M7.5 10h9v6h-9Z");
}

.jrpnc2pnl {
  d: path("M15 5h3a3 3 0 0 1 3 3v10a3 3 0 0 1 -3 3H6a3 3 0 0 1 -3 -3V8a3 3 0 0 1 3 -3h3");
}

.k5avrj3uw {
  fill: currentColor;
  d: path("M7.5 10h9v6h-9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.n1c_-nuwx {
  d: path("m7.5 10 4.5 4.5 4.5 -4.5");
}

.z92okmbgh {
  fill: currentColor;
  d: path("M15 5h3a3 3 0 0 1 3 3v10a3 3 0 0 1 -3 3H6a3 3 0 0 1 -3 -3V8a3 3 0 0 1 3 -3h3");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
