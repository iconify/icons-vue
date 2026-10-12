<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="mt9gbccho"/><path class="x9eatmb0p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:washer-fluid" /></template>
<style>
.mt9gbccho {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.75 14.5l1.75-8c.2-.9 1-1.5 1.9-1.5h11.2c.9 0 1.7.6 1.9 1.5l1.75 8Zm9.25 0l-3.75-6M12 21.25v-3.5");
}

.x9eatmb0p {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.5 18.75h.01M9.5 17h.01m4.99 0h.01m1.99 1.75h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
