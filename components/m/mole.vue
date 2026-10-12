<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="ioh_m-1ng"/><path class="hvcrdn6wo"/><path class="i-09z4cpn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mole" /></template>
<style>
.hvcrdn6wo {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.5 16.4l-1 3.85h3.25l.5-3.25M13 17l-.5 3.25H16l.25-3.25");
}

.i-09z4cpn {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.75 11h.01");
}

.ioh_m-1ng {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 12.5L8.5 9.25C10 8 11.75 7.5 13.5 7.5c4.25 0 7.5 2.75 7.5 6c0 2-1.5 3.5-3.5 3.5H10q-2.25 0-3.75-1.5l-3-1.75a.75.75 0 0 1 0-1.25");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
