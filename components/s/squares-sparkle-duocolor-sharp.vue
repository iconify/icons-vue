<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vd5e6cbev"/><path class="zli4k3a_w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:squares-sparkle-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vd5e6cbev {
  stroke-opacity: 0.4;
  d: path("M18 3c0 1 2 3 3 3c-1 0-3 2-3 3c0-1-2-3-3-3c1 0 3-2 3-3");
}

.zli4k3a_w {
  d: path("M3 3h6v6H3Zm0 12h6v6H3Zm12 0h6v6h-6Z");
}

</style>
