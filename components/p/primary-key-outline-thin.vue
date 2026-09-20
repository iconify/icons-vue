<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="askgmhbjk"/><path class="t5z055brv"/><path class="adx_66b5y"/><path class="w2dozdlxo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:primary-key-outline-thin" /></template>
<style>
.adx_66b5y {
  d: path("M13 7v3");
}

.askgmhbjk {
  d: path("M3 7a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t5z055brv {
  d: path("M7 7h8");
}

.w2dozdlxo {
  d: path("M2 14a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

</style>
