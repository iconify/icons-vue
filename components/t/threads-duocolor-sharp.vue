<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xdk0a2pfa"/><path class="sj2qpk-ph"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:threads-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sj2qpk-ph {
  d: path("M12.5 11c-2.5 0-3 1.25-3 2.5c0 1.5 1 2.5 2.5 2.5c2.5 0 3.5-1.5 3.5-5s-2-4-3-4s-1.83.33-2.5 1");
}

.xdk0a2pfa {
  stroke-opacity: 0.4;
  d: path("M19.5 7.5c-1.33-3-3.67-4.5-7-4.5c-5 0-8 2.5-8 9s3.5 9 8 9s7-3 7-5s-1-5-7-5");
}

</style>
