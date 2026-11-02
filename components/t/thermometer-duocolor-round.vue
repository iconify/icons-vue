<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rtfbuubui"/><path class="njoo6ks6c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:thermometer-duocolor-round" /></template>
<style>
.njoo6ks6c {
  d: path("M7 12V5a2 2 0 1 1 4 0v7a4.472 4.472 0 1 1-4 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rtfbuubui {
  stroke-opacity: 0.4;
  d: path("M15 4h4m-4 3h2m-2 3h4");
}

</style>
