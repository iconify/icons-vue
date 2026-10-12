<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="z9rbk6z9b"/><rect class="wwzxtc4_c"/><path class="lbi_8eh0n"/><path class="eev_56b6j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:portable-toilet" /></template>
<style>
.eev_56b6j {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13.5 15.5h.01");
}

.lbi_8eh0n {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 21.25V9.5h7v11.75");
}

.wwzxtc4_c {
  width: 13px;
  height: 14.75px;
  x: 5.5px;
  y: 6.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.z9rbk6z9b {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 6.5C4.25 4 7.5 2.75 12 2.75S19.75 4 19.75 6.5Z");
}

</style>
