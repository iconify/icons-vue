<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="wrnmfs0xk"/><path class="l4_xaerby"/><path class="mg9swtnzs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:study-lamp" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l4_xaerby {
  d: path("m8.5 18.75l-3-6.25l6.5-6");
}

.mg9swtnzs {
  d: path("m12.9 5.95l-.8.6q-.8.6-.55 1.57l1.1 4.36q.25.97 1.05.37l4.8-3.6q.8-.6-.06-1.11l-3.88-2.28q-.86-.51-1.66.09");
}

.wrnmfs0xk {
  width: 9.5px;
  height: 2.5px;
  x: 3.75px;
  y: 18.75px;
  rx: 1.25px;
}

</style>
