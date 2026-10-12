<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="frx_tqwly"/><path class="g4mhskbls"/><path class="a1pbthbbp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ocarina" /></template>
<style>
.a1pbthbbp {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.5 11.25h.01m3.24-1h.01m3.24 1h.01m-3.26 3.5h.01");
}

.frx_tqwly {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 12.5a7.75 5.5 0 1 0 15.5 0a7.75 5.5 0 1 0-15.5 0");
}

.g4mhskbls {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.15 10.75h-2.4a1 1 0 0 0-1 1v1.5a1 1 0 0 0 1 1h2.4");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
