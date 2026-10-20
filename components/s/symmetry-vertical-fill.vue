<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="yblwo8bwk"/><path class="xdk9_oksp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:symmetry-vertical-fill" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xdk9_oksp {
  d: path("M2 12L22 12");
}

.yblwo8bwk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4 9L4 7.6832C4 6.8592 4.5054 6.1195 5.273 5.82L17.2731 1.1377C17.5047 1.0473 17.7513 1.0009 18 1.0009C19.1045 1.0009 20 1.8963 20 3.0009L20 9L4 9ZM20 15L20 20.9991C20 22.1036 19.1046 22.999 18.0001 22.999C17.7513 22.999 17.5047 22.9526 17.273 22.8622L5.2729 18.18C4.5053 17.8804 4 17.1408 4 16.3168L4 15L20 15Z");
  stroke: none;
}

</style>
