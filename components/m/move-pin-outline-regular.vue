<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qad3kqbgr"/><path class="jtt8g10_o"/><path class="c_tajwbcn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:move-pin-outline-regular" /></template>
<style>
.c_tajwbcn {
  d: path("M12.5 7.5 15 10l-2.5 2.5");
}

.jtt8g10_o {
  d: path("M9 10h6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qad3kqbgr {
  d: path("M4 10a8 8 0 0 1 16 0l-8 8Z");
}

</style>
