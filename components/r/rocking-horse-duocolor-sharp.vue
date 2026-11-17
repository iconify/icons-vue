<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fn6u3cfgf"/><path class="vkiqw-b_o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:rocking-horse-duocolor-sharp" /></template>
<style>
.fn6u3cfgf {
  stroke-opacity: 0.4;
  d: path("M3 15a11.402 11.402 0 0 0 18 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vkiqw-b_o {
  d: path("m5 17l2-6l-1-2l-2 1l-1-2l2-4a6 6 0 0 1 6 6h6l2 7m-4 2l-1-4h-4l-1 4m8-9h1a3 3 0 0 0 3-3");
}

</style>
