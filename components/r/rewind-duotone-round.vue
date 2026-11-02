<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="jd0qq9bjp"/><path class="kzgj13umy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:rewind-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.jd0qq9bjp {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m3.971 10.285l5-3A1.999 1.999 0 0 1 12 9v2.999c0-.709.359-1.355.971-1.714l5-3A1.999 1.999 0 0 1 21 9v6a2 2 0 0 1-3.029 1.715l-5-3A1.97 1.97 0 0 1 12 12.001V15a2 2 0 0 1-3.029 1.715l-5-3a2 2 0 0 1 0-3.43");
}

.kzgj13umy {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m17.971 7.285l-5 3c-1.295.777-1.295 2.653 0 3.43l5 3c1.333.8 3.029-.16 3.029-1.715V9c0-1.555-1.696-2.515-3.029-1.715m-9 0l-5 3c-1.295.777-1.295 2.653 0 3.43l5 3c1.333.8 3.029-.16 3.029-1.715V9c0-1.555-1.696-2.515-3.029-1.715");
}

</style>
