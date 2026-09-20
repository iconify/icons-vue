<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g7d56fjnv"/><path class="njx-i5bnu"/><path class="a_0xpnjsq"/><path class="vyks9vbfn"/><path class="ogtwkzbca"/><path class="eahy924ne"/><path class="zjleuacmi"/><path class="lxoo1ac9h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:tip-calc-duotone-thin" /></template>
<style>
.a_0xpnjsq {
  fill: currentColor;
  d: path("M10 14.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.eahy924ne {
  d: path("M6 9.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.g7d56fjnv {
  fill: currentColor;
  d: path("M2 6a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lxoo1ac9h {
  d: path("M10 14.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.njx-i5bnu {
  fill: currentColor;
  d: path("M6 9.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ogtwkzbca {
  d: path("M22 9.5h-7v5h7");
}

.vyks9vbfn {
  d: path("M2 6a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.zjleuacmi {
  d: path("m6.5 14.5 5 -5");
}

</style>
