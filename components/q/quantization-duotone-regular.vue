<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gwsin5eat"/><path class="naqjrf_pr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:quantization-duotone-regular" /></template>
<style>
.gwsin5eat {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 18h4v-4h4v-4h4V6h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.naqjrf_pr {
  d: path("M4 18h4v-4h4v-4h4V6h4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
