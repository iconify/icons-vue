<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="khounccao"/><path class="lqt5w6d4w"/><path class="jh7uflb5k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:recurring-event" /></template>
<style>
.jh7uflb5k {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.75 17.5a2.75 2.75 0 1 0 2.75-2.75h-1.75M17 13.5l-1.25 1.25L17 16");
}

.khounccao {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.75 20.25h-5.5a2.5 2.5 0 0 1-2.5-2.5v-10a2.5 2.5 0 0 1 2.5-2.5h11.5a2.5 2.5 0 0 1 2.5 2.5v4M3.75 10h16.5M8 2.75v4.5m8-4.5v4.5");
}

.lqt5w6d4w {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 14h.01M12 14h.01M8 17h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
