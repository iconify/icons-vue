<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="aihfrab2h"/><path class="p_fx4v1ly"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:metabolism" /></template>
<style>
.aihfrab2h {
  d: path("M17.785 5.106a9 9 0 1 1-8.863-1.563");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p_fx4v1ly {
  d: path("M6.5 3L9 5.25l-2.25 2.5M12 7c2.75 2.5 3.75 4 3.75 6c0 2.25-1.5 3.75-3.75 3.75S8.25 15.25 8.25 13q0-1.875 1.5-3c0 1.25.75 2 1.5 2c0-1.75-.25-3.5.75-5");
}

</style>
