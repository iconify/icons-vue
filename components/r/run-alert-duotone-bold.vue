<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="oe5qucsjr"/><path class="es0og7-jz"/><path class="brpj2xbjm"/><path class="bskrurb1h"/><path class="s8vehckhm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:run-alert-duotone-bold" /></template>
<style>
.brpj2xbjm {
  d: path("M4 5v14l7 -7Z");
}

.bskrurb1h {
  d: path("M18 7v5");
}

.es0og7-jz {
  fill: currentColor;
  d: path("M17 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.oe5qucsjr {
  fill: currentColor;
  d: path("M4 5v14l7 -7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.s8vehckhm {
  d: path("M17 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
