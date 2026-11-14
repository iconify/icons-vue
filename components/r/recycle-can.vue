<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cg6ce9ywd"/><path class="sj2futumf"/><path class="lg5tegbmn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:recycle-can" /></template>
<style>
.cg6ce9ywd {
  d: path("M12 18.285v.215L10.5 21h-6L3 18.5V5l1.5-2.5h6L12 5v9.685m0 .2v2.6M3 5h9m4.888 16.054a3.25 3.25 0 0 1-.513-5.869");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lg5tegbmn {
  d: path("m21.25 21.25l-1.75-.5L20 19");
}

.sj2futumf {
  d: path("m14.75 14.75l1.75.5L16 17m3.112-2.054a3.25 3.25 0 0 1 .513 5.869");
}

</style>
