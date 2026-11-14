<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nsmb_fbdz"/><path class="elrjfrbyj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pension-contribution" /></template>
<style>
.elrjfrbyj {
  d: path("M11 5v1.5c0 .85 1.55 1.5 3.5 1.5S18 7.35 18 6.5V5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nsmb_fbdz {
  d: path("m5.5 3.5l2 10h9m-7.75 0L6 18.25m9.5-4.75l2 5m3.501-1.881a15.5 15.5 0 0 1-18.002 0M11 5a3.5 1.5 0 1 0 7 0a3.5 1.5 0 1 0-7 0");
}

</style>
