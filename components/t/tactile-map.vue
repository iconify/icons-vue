<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="pi-3boh5r"/><path class="lurr01srd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tactile-map" /></template>
<style>
.lurr01srd {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.75 9h.01m-.01 3.5h.01m6.24-3h.01M12 13h.01m6.24-3h.01m-.01 3.5h.01");
}

.pi-3boh5r {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.45 4.73L7.8 3.02q.7-.27 1.41-.04l5.58 1.79q.71.23 1.41-.04l4.35-1.71q.7-.27.7.48v14.75q0 .75-.7 1.02l-4.35 1.71q-.7.27-1.41.04l-5.58-1.79q-.71-.23-1.41.04l-4.35 1.71q-.7.27-.7-.48V5.75q0-.75.7-1.02M8.5 3v16m7-14v16");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
