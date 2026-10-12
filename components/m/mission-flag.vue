<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cetklsjxm"/><circle class="z-rqkpu3s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mission-flag" /></template>
<style>
.cetklsjxm {
  d: path("M5.25 21.25v-18m0 .5h13.5l-2.5 4l2.5 4H5.25Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z-rqkpu3s {
  cx: 10.75px;
  cy: 7.75px;
  r: 1.75px;
}

</style>
