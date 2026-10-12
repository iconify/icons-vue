<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jdx6jwbej"/><circle class="ygzhjxbkl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tag" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jdx6jwbej {
  d: path("M3.75 5.75a2 2 0 0 1 2-2h5.4a2 2 0 0 1 1.41.59l7.6 7.6a2 2 0 0 1 0 2.82l-5.43 5.43a2 2 0 0 1-2.82 0l-7.6-7.6a2 2 0 0 1-.56-1.41Z");
}

.ygzhjxbkl {
  cx: 8px;
  cy: 8px;
  r: 1.25px;
}

</style>
