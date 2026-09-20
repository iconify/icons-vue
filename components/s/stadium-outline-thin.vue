<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tlag47v4y"/><path class="niggb1byh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:stadium-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.niggb1byh {
  d: path("M8 10h8v4H8Z");
}

.tlag47v4y {
  d: path("M12 4c6 0 10 3 10 8s-4 8 -10 8 -10 -3 -10 -8 4 -8 10 -8");
}

</style>
