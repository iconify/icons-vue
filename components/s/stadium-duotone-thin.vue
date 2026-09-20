<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jer_tk4og"/><path class="r9vsub3-y"/><path class="tlag47v4y"/><path class="niggb1byh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:stadium-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jer_tk4og {
  fill: currentColor;
  d: path("M12 4c6 0 10 3 10 8s-4 8 -10 8 -10 -3 -10 -8 4 -8 10 -8");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.niggb1byh {
  d: path("M8 10h8v4H8Z");
}

.r9vsub3-y {
  fill: currentColor;
  d: path("M8 10h8v4H8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.tlag47v4y {
  d: path("M12 4c6 0 10 3 10 8s-4 8 -10 8 -10 -3 -10 -8 4 -8 10 -8");
}

</style>
