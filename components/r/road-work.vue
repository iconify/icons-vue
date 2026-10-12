<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="fhvjqwado"/><path class="mubwpwb3i"/><path class="ub4bxk3ds"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:road-work" /></template>
<style>
.fhvjqwado {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.98 4.99l7.29 13.02q.98 1.74-1.02 1.74H4.75q-2 0-1.02-1.74l7.29-13.02q.98-1.74 1.96 0");
}

.mubwpwb3i {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.75 10h.01");
}

.ub4bxk3ds {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m10.75 11.75l-.75 3l-1.5 3m1.5-3l1.5 3m-1-5.25l2.75 1.25m0 0l1.5 3m-.75 1.5l1.25-1.5l2 1.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
