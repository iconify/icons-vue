<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hmwrvubhz"/><path class="c7kjqqh8k"/><path class="dsyn-2b9s"/><path class="nnj9-vbsr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pin-off-duotone-thin" /></template>
<style>
.c7kjqqh8k {
  d: path("M7 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.dsyn-2b9s {
  d: path("M10 10v7");
}

.hmwrvubhz {
  fill: currentColor;
  d: path("M7 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
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

.nnj9-vbsr {
  d: path("M5 21 19 7");
}

</style>
