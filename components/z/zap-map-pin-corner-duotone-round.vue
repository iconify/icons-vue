<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="c8ymodb8s"/><path class="uq4vc_b0m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zap-map-pin-corner-duotone-round" /></template>
<style>
.c8ymodb8s {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M13.75 10H17a6 6 0 0 0-5.886 4.834l-.676 3.416l-.943 1.185A.699.699 0 0 1 8.25 19v-3a2 2 0 0 0-2-2H5a.965.965 0 0 1-.755-1.565l6.26-7.87A.699.699 0 0 1 11.75 5v3a2 2 0 0 0 2 2M17 21c-1.574-1.051-2.999-3.053-3-5a3 3 0 1 1 6 0c-.001 1.947-1.426 3.949-3 5");
}

.ft5dv1b6b {
  fill: none;
}

.uq4vc_b0m {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17 10h-3.25a2 2 0 0 1-2-2V5c0-.661-.833-.952-1.245-.435l-6.26 7.87A.965.965 0 0 0 5 14h1.25a2 2 0 0 1 2 2v3c0 .661.833.952 1.245.435l.943-1.185M17 21c-1.5-1-3-3-3-5a3 3 0 0 1 6 0c0 2-1.5 4-3 5m0-5h.01");
}

</style>
