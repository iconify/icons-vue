<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dukgchbwq"/><path class="iob2sxbnt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pencil-ruler-duocolor-sharp" /></template>
<style>
.dukgchbwq {
  stroke-opacity: 0.4;
  d: path("M13 7L9 3L3 9l4 4m10-2l4 4l-6 6l-4-4");
}

.iob2sxbnt {
  d: path("M4 16L16 4l4 4L8 20m0 0H4v-4m7-11L9 7m10 6l-2 2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
