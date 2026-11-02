<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pjc7nwbke"/><path class="le3mv3bds"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:running-duocolor" /></template>
<style>
.le3mv3bds {
  d: path("m12 9l-2 5l4 3v4m-4-7l-2 4l-4-1m3-5l1-3h4l3 3h5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pjc7nwbke {
  stroke-opacity: 0.4;
  d: path("M14 5a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

</style>
