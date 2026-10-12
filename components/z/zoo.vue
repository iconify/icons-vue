<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="jy2cdy0eh"/><path class="t598jgb9p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:zoo" /></template>
<style>
.jy2cdy0eh {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 3.5h17.5M3.25 21.25h17.5M4.5 3.5v17.75m15-17.75v17.75M12 13c-1.75 0-3.75 2.25-3.75 4c0 1 .75 1.75 1.75 1.75c.75 0 1.25-.35 2-.35s1.25.35 2 .35c1 0 1.75-.75 1.75-1.75c0-1.75-2-4-3.75-4");
}

.t598jgb9p {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.25 11.25h.01m2.24-3h.01m2.99 0h.01m2.24 3h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
