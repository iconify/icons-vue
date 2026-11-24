<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zmn024b9o"/><path class="ex500pb8k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:user-headset-duocolor-sharp" /></template>
<style>
.ex500pb8k {
  d: path("M8 10a4 4 0 1 0 8 0a4 4 0 0 0-8 0M4 21c0-2.21 3.582-4 8-4s8 1.79 8 4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.zmn024b9o {
  stroke-opacity: 0.4;
  d: path("M5 10a7 7 0 0 1 14 0M5 10H3v4h2zm14 0h2v4h-2zm1 4v1h-2");
}

</style>
