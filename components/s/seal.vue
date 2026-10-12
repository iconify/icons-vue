<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="v281qibzw"/><path class="ehhecpeag"/><path class="puv_-tb8h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:seal" /></template>
<style>
.ehhecpeag {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.75 5.75h.01M3.75 7h.01");
}

.puv_-tb8h {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 20.25h18.5");
}

.v281qibzw {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 7c.5-2 2.25-3.75 4.5-3.75s3.5 1.75 3.5 4c0 3.25 1.75 6.25 5.25 8l4.25 1.5l-1.5 3.5C17.5 18 14.25 17.5 11 17.5l-3.5 2.75l1-4.75c-.75-2-1.25-4-1-5.5S6 8 3.75 7");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
