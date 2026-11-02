<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mw-od1tqk"/><path class="jho1-obgv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-dashed-square-duocolor-sharp" /></template>
<style>
.jho1-obgv {
  d: path("M3 6V3h3m12 0h3v3m0 12v3h-3M10 3h4m7 7v4");
}

.mw-od1tqk {
  stroke-opacity: 0.4;
  d: path("M3 10h11v11H3Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
