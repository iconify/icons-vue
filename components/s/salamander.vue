<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="sizbywbiv"/><path class="h5u1zbbrr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:salamander" /></template>
<style>
.h5u1zbbrr {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 12.5h.01m3.49 0h.01m-9.76-1h.01");
}

.sizbywbiv {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 12.25c0-1.75 1.5-3 3.25-3c1.25 0 2.25.5 3 1.25h5c2.75 0 4.5 1 6 2.75l1 1.25c.25.3 0 .75-.4.7c-1.6-.2-3.6-.7-6.1-.7H9c-.75.75-1.75 1.25-3 1.25c-1.75 0-3.25-1.5-3.25-3.5M9.5 14.5L8 17.75m7.25-3.25l1 3.25");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
