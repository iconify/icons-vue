<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="al8spfbtw"/><path class="kti8gwi-u"/><rect class="u6r3jabeh"/><path class="dzuzjs4oc"/><rect class="cx3lxzbrl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sander" /></template>
<style>
.al8spfbtw {
  width: 9.5px;
  height: 3.25px;
  x: 7.25px;
  y: 5.25px;
  rx: 1.625px;
}

.cx3lxzbrl {
  width: 18.5px;
  height: 3.25px;
  x: 2.75px;
  y: 18px;
  rx: 1px;
}

.dzuzjs4oc {
  d: path("M19.25 13.25h2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kti8gwi-u {
  d: path("M10 8.5v3m4-3v3");
}

.u6r3jabeh {
  width: 14.5px;
  height: 3.5px;
  x: 4.75px;
  y: 11.5px;
  rx: 1.25px;
}

</style>
