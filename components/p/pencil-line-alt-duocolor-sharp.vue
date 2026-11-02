<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hvuoh6b3h"/><path class="fuj90uofq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pencil-line-alt-duocolor-sharp" /></template>
<style>
.fuj90uofq {
  d: path("M4 20v-4L16 4l4 4L8 20z");
}

.hvuoh6b3h {
  stroke-opacity: 0.4;
  d: path("M8 20h12");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
