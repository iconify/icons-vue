<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kp42mccma"/><path class="zd0mcdxvh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shapes-duocolor-sharp" /></template>
<style>
.kp42mccma {
  stroke-opacity: 0.4;
  d: path("m8 4l4 6H4Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.zd0mcdxvh {
  d: path("M3 15h6v6H3Zm10 2a4 4 0 1 0 8 0a4 4 0 0 0-8 0");
}

</style>
