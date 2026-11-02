<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gkxwt_b1d"/><path class="yhdsbe0jv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:playlist-duocolor-sharp" /></template>
<style>
.gkxwt_b1d {
  stroke-opacity: 0.4;
  d: path("M15 10v8l6-4z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.yhdsbe0jv {
  d: path("M3 6h18M3 12h8m-8 6h8");
}

</style>
