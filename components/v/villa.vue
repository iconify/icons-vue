<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="w1k-3mbui"/><path class="t117yfb_y"/><path class="mhu4k1brd"/><path class="osef5fu9r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:villa" /></template>
<style>
.mhu4k1brd {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.5 12h.01m7.99 0h.01");
}

.osef5fu9r {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 20.25q1.15-.9 2.3 0t2.3 0t2.3 0t2.3 0t2.3 0t2.3 0t2.3 0t2.3 0");
}

.t117yfb_y {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 16.25v-3a1.5 1.5 0 0 1 3 0v3");
}

.w1k-3mbui {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 15.45V9.8q0-.8-.5-.8t-.04-.66l2.58-3.68Q6.25 4 7.05 4h6.9q.8 0 1.26.66l2.58 3.68q.46.66-.04.66t-.5.8v5.65q0 .8-.8.8H4.55q-.8 0-.8-.8");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
