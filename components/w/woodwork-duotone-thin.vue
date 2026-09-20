<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fau4mhlla"/><path class="f82c7tb8u"/><path class="qf1y30bjf"/><path class="ic_pehd5a"/><path class="ezh2fvb-c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:woodwork-duotone-thin" /></template>
<style>
.ezh2fvb-c {
  d: path("M6 17c3 -3 7 -3 10 0");
}

.f82c7tb8u {
  d: path("M4 6v5h10V6Z");
}

.fau4mhlla {
  fill: currentColor;
  d: path("M4 6v5h10V6Z");
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

.ic_pehd5a {
  d: path("M3 17h18");
}

.qf1y30bjf {
  d: path("M14 8.5h5");
}

</style>
