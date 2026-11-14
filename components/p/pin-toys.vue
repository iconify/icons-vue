<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gt3js0blt"/><path class="nstprgbih"/><path class="bj0ho8z3v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pin-toys" /></template>
<style>
.bj0ho8z3v {
  d: path("M7 14a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

.gt3js0blt {
  d: path("M4.5 7h11A1.5 1.5 0 0 1 17 8.5v11a1.5 1.5 0 0 1-1.5 1.5h-11A1.5 1.5 0 0 1 3 19.5v-11A1.5 1.5 0 0 1 4.5 7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nstprgbih {
  d: path("m3 7l4-4h14v14l-4 4m0-14l4-4");
}

</style>
