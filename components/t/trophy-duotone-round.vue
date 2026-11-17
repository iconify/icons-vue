<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="hoyr9ibsg"/><path class="maurpwbkp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:trophy-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hoyr9ibsg {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M7 9V5a2 2 0 0 1 2-2h6a2 2 0 0 1 2 2v4a5 5 0 0 1-3 4.584V13h-4v.584A5 5 0 0 1 7 9m3 7v-2.416a5.03 5.03 0 0 0 4 0V16c0 2 3 2 3 5H7c0-3 3-3 3-5");
}

.maurpwbkp {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 9V5a2 2 0 0 1 2-2h6a2 2 0 0 1 2 2v4A5 5 0 0 1 7 9m3 5v2c0 2-3 2-3 5m7-7v2c0 2 3 2 3 5M6 21h12M7 5H5a2 2 0 1 0 0 4h2m10-4h2a2 2 0 1 1 0 4h-2");
}

</style>
