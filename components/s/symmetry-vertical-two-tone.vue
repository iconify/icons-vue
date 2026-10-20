<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="c8a5djbgw"/><path class="dsivjbcrc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:symmetry-vertical-two-tone" /></template>
<style>
.c8a5djbgw {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 16.3168L4 7.6832C4 6.8592 4.5054 6.1195 5.273 5.82L17.2731 1.1377C17.5047 1.0473 17.7513 1.0009 18 1.0009C19.1045 1.0009 20 1.8963 20 3.0009L20 20.9991C20 22.1036 19.1046 22.999 18.0001 22.999C17.7513 22.999 17.5047 22.9526 17.273 22.8622L5.2729 18.18C4.5053 17.8804 4 17.1408 4 16.3168Z");
  stroke: none;
}

.dsivjbcrc {
  d: path("M5 16.3168L5 7.6832C5 7.2712 5.2527 6.9014 5.6365 6.7516L17.6365 2.0693C18.2922 1.8135 19 2.2971 19 3.0009L19 20.9991C19 21.7029 18.2922 22.1865 17.6365 21.9306L5.6365 17.2484C5.2527 17.0986 5 16.7288 5 16.3168ZM2 12L22 12");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
