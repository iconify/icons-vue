<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xuzysxbsg"/><path class="bjgu-ac-j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:moon-star" /></template>
<style>
.bjgu-ac-j {
  d: path("M16.5 3.5q0 4 4 4q-4 0-4 4q0-4-4-4q4 0 4-4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xuzysxbsg {
  d: path("M20 14.75A8.5 8.5 0 1 1 9.25 4A9 9 0 0 0 20 14.75");
}

</style>
