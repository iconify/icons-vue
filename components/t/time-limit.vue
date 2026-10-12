<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="c6vt1lbds"/><path class="iuzv7rbol"/><path class="g2lyadblk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:time-limit" /></template>
<style>
.c6vt1lbds {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.g2lyadblk {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m18.06 15.5l1.95 1.13");
}

.iuzv7rbol {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 12V7.5a4.5 4.5 0 0 1 3.9 6.75Z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
