<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="te3ifc1by"/><path class="dsy_cw4ql"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:temperature-celsius-duocolor-sharp" /></template>
<style>
.dsy_cw4ql {
  d: path("M21 8a3 3 0 0 0-3-3h-2a3 3 0 0 0-3 3v8a3 3 0 0 0 3 3h2a3 3 0 0 0 3-3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.te3ifc1by {
  stroke-opacity: 0.4;
  d: path("M3 7a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

</style>
