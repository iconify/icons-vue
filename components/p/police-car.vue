<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="nh15idf2m"/><path class="f35_vn1ti"/><rect class="obcigeb_s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:police-car" /></template>
<style>
.f35_vn1ti {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.5 16.25h.01m8.99 0h.01");
}

.nh15idf2m {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 14.5L5.4 9.6a2 2 0 0 1 1.9-1.35h9.4a2 2 0 0 1 1.9 1.35l1.65 4.9v4a1 1 0 0 1-1 1H4.75a1 1 0 0 1-1-1Zm2.75 5v1.75m11-1.75v1.75m-13.25-8h15.5");
}

.obcigeb_s {
  width: 5.5px;
  height: 2.5px;
  x: 9.25px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.25px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
