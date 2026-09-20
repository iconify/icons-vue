<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mxpxejnja"/><path class="su9etdbad"/><path class="uidmmjb0u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:threat-hunt-outline-regular" /></template>
<style>
.mxpxejnja {
  d: path("M3 5h8v6l-4 4 -4 -4Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.su9etdbad {
  d: path("M14 10a3.5 3.5 0 1 0 7 0 3.5 3.5 0 1 0 -7 0");
}

.uidmmjb0u {
  d: path("m20 12.5 2 2");
}

</style>
