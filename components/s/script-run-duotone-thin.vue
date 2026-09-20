<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ly2hozbzp"/><path class="tvpgdo31a"/><path class="dpvrwwhil"/><path class="iyltd-baj"/><path class="mi_m6achy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:script-run-duotone-thin" /></template>
<style>
.dpvrwwhil {
  d: path("M5 9h8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iyltd-baj {
  d: path("M5 13h6");
}

.ly2hozbzp {
  fill: currentColor;
  d: path("M2 6a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.mi_m6achy {
  d: path("m17 9 3 3 -3 3");
}

.tvpgdo31a {
  d: path("M2 6a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

</style>
