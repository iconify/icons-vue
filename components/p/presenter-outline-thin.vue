<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bol6i856t"/><path class="jz2wn7nic"/><path class="flc5_hbok"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:presenter-outline-thin" /></template>
<style>
.bol6i856t {
  d: path("M3 7a2 2 0 0 1 2 -2h9a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.flc5_hbok {
  d: path("M15 17a3.5 3.5 0 0 1 7 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jz2wn7nic {
  d: path("M16.5 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
