<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="a9joe4job"/><path class="kaj194bxv"/><path class="viu3swbad"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:zebra" /></template>
<style>
.a9joe4job {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 5.25q1.65 0 3 .6L18.25 3c.4 1.6 0 3.4-1.2 4.6c.3.8.45 1.6.45 2.65c0 2.1-.85 3.6-1.5 5.5V17a4 4 0 0 1-8 0v-1.25c-.65-1.9-1.5-3.4-1.5-5.5c0-1.05.15-1.85.45-2.65c-1.2-1.2-1.6-3-1.2-4.6L9 5.85q1.35-.6 3-.6");
}

.kaj194bxv {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9.5 7.75l2.5 1.5l2.5-1.5m-7.4 3.5c1.75 0 3.25.5 4.9 1.5c1.65-1 3.15-1.5 4.9-1.5m-8.5 3.5c1.25 0 2.5.25 3.6 1c1.1-.75 2.35-1 3.6-1");
}

.viu3swbad {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.25 18.5h.01m3.49 0h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
