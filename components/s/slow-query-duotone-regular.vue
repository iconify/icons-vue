<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="f346nu0ok"/><path class="llc-u9kbe"/><path class="yjzepunpt"/><path class="f_-gw6caf"/><path class="gh7xyhbdv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:slow-query-duotone-regular" /></template>
<style>
.f_-gw6caf {
  d: path("M11 7v4");
}

.f346nu0ok {
  fill: currentColor;
  d: path("M5 11a6 6 0 1 0 12 0 6 6 0 1 0 -12 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.gh7xyhbdv {
  d: path("M11 11h3");
}

.llc-u9kbe {
  d: path("M5 11a6 6 0 1 0 12 0 6 6 0 1 0 -12 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.yjzepunpt {
  d: path("M15.5 15.5 20 20");
}

</style>
