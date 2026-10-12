<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n36l1ac9w"/><rect class="mk3gr2syb"/><path class="hyyl6ybry"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mirror-hand" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hyyl6ybry {
  d: path("M8.75 8.5a3.25 3 0 0 1 3.25-3");
}

.mk3gr2syb {
  width: 2.5px;
  height: 8px;
  x: 10.75px;
  y: 13.25px;
  rx: 1.25px;
}

.n36l1ac9w {
  d: path("M12 3a6 5.5 0 1 1 0 11a6 5.5 0 1 1 0-11");
}

</style>
