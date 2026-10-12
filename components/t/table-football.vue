<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="dxxnv74zz"/><path class="te3q-0q3c"/><path class="tb6q2fbtf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:table-football" /></template>
<style>
.dxxnv74zz {
  width: 15.5px;
  height: 15.5px;
  x: 4.25px;
  y: 4.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

.tb6q2fbtf {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 15.75h.01");
}

.te3q-0q3c {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 12h18.5M8.5 9.5v5m7-5v5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
