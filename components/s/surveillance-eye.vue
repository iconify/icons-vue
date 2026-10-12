<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="az4yhpbss"/><circle class="js3xdyw7g"/><path class="fyzvyrjwu"/><path class="ddyow6iqr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:surveillance-eye" /></template>
<style>
.az4yhpbss {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 14.5C5.75 11 8.65 9 12 9s6.25 2 8.25 5.5c-2 3.5-4.9 5.5-8.25 5.5s-6.25-2-8.25-5.5");
}

.ddyow6iqr {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3v2.5m-5.5-.75l1.25 2m9.75-2l-1.25 2");
}

.fyzvyrjwu {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 14.5h.01");
}

.js3xdyw7g {
  cx: 12px;
  cy: 14.5px;
  r: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
