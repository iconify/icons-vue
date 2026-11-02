<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="w-h6ynb5v"/><path class="feijlt7er"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pencil-duocolor-sharp" /></template>
<style>
.feijlt7er {
  d: path("M4 16L16 4l4 4L8 20m4-12l4 4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.w-h6ynb5v {
  stroke-opacity: 0.4;
  d: path("M8 20H4v-4");
}

</style>
