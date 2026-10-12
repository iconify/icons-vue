<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dmf78xbso"/><rect class="z2t9cfb1g"/><path class="cjr9q-b5s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:studio-apartment" /></template>
<style>
.cjr9q-b5s {
  d: path("M15 7.5h2.25M13.5 9.75h5.25");
}

.dmf78xbso {
  d: path("M7 21.25H2.75V2.75h18.5v18.5H12.5m0 0v-5.5M7 21.25a5.5 5.5 0 0 1 5.5-5.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z2t9cfb1g {
  width: 5.25px;
  height: 8.5px;
  x: 13.5px;
  y: 5.25px;
  rx: 1px;
}

</style>
