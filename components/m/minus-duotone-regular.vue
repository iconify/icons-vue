<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="u-kmlrghs"/><path class="sxlwlmkmh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:minus-duotone-regular" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sxlwlmkmh {
  d: path("M4 12h16");
}

.u-kmlrghs {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 12h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
