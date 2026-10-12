<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="yu69su-po"/><rect class="jpcx9gbef"/><path class="ald18pbar"/><path class="dpvempfvy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:planetarium" /></template>
<style>
.ald18pbar {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 21.25v-3.5h3v3.5");
}

.dpvempfvy {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 5.5h.01M20 5.5h.01M12 3h.01");
}

.jpcx9gbef {
  width: 17.5px;
  height: 7.5px;
  x: 3.25px;
  y: 13.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yu69su-po {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 13.75a6.75 6.75 0 0 1 13.5 0Z");
}

</style>
