<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="fbzeghb4q"/><path class="q14_0brox"/><path class="iu0ag9bjl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:suit" /></template>
<style>
.fbzeghb4q {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 3.25h5.5q1.5 0 2.77.79l1.46.92q1.27.79 1.37 2.29l.8 12q.1 1.5-1.4 1.5H4.25q-1.5 0-1.4-1.5l.8-12q.1-1.5 1.37-2.29l1.46-.92q1.27-.79 2.77-.79");
}

.iu0ag9bjl {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 17.5h.01");
}

.q14_0brox {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8 3.75l4 10.75l4-10.75");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
