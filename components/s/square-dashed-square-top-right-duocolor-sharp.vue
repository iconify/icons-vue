<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="g1-zcigad"/><path class="n3fr3bc5y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-dashed-square-top-right-duocolor-sharp" /></template>
<style>
.g1-zcigad {
  stroke-opacity: 0.4;
  d: path("M10 3h11v11H10Z");
}

.n3fr3bc5y {
  d: path("M3 6V3h3m15 15v3h-3M6 21H3v-3m11 3h-4m-7-7v-4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
