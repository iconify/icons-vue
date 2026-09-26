<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="u52ozydly"/><path class="x3pit_b5m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:smartphone-check-duotone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.u52ozydly {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M15 1C17.7614 1 20 3.23858 20 6V12C20 12.5523 19.5523 13 19 13H13C11.3431 13 10 14.3431 10 16V22C10 22.5523 9.5523 23 9 23C6.23858 23 4 20.7614 4 18V6C4 3.23858 6.23858 1 9 1H15Z");
  stroke: none;
}

.x3pit_b5m {
  d: path("M13 19.6L15.3333 22L19 16M13.5 6L10.5 6");
}

</style>
