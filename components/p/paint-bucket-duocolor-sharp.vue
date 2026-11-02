<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xsgqi2bof"/><path class="wlqp9fbml"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:paint-bucket-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wlqp9fbml {
  d: path("m11 6l6 6l-8 8l-6-6zM8 3l3 3");
}

.xsgqi2bof {
  stroke-opacity: 0.4;
  d: path("M5 12h12m4 7a2 2 0 1 1-4 0c0-1 1-2 2-3c1 1 2 2 2 3");
}

</style>
