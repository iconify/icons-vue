<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ihfmldtqc"/><path class="jbky7xpdt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:map-pin-duotone" /></template>
<style>
.ihfmldtqc {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18.708204 16L12.745356 22.666667C12.555648 22.878767 12.284562 23 12 23C11.715438 23 11.444352 22.878767 11.254644 22.666667L5.291796 16C3.815931 14.349933 3 12.213797 3 10C3 5.029437 7.029437 1 12 1C16.970563 1 21 5.029437 21 10C21 12.213797 20.184069 14.349933 18.708204 16Z");
  stroke: none;
}

.jbky7xpdt {
  d: path("M15 10C15 11.6569 13.6569 13 12 13C10.3431 13 9 11.6569 9 10C9 8.3431 10.3431 7 12 7C13.6569 7 15 8.3431 15 10Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
