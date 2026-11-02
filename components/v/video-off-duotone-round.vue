<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mp85_kbvo"/><path class="w394mfwrb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:video-off-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mp85_kbvo {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m15.77 8.497l.783-.391c1.12-.56 2.457-.597 3.583-.034c.534.267.996.658 1.328 1.154c.352.527.536 1.141.536 1.774v6a1 1 0 0 1-1.447.894L16 15.618V16a3 3 0 0 1-3 3H7a5 5 0 0 1-5-5V8a3 3 0 0 1 3-3h6a5.01 5.01 0 0 1 4.77 3.497");
}

.w394mfwrb {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15 16c-.628 1.388-2.378 2-4 2H7a4 4 0 0 1-4-4v-4c0-1.622.612-3.372 2-4m6 0a4 4 0 0 1 4 4m0 0l2-1c1.838-.919 4 .162 4 2v2c0 .828-.35 1.593-1 2M2 3l19 19");
}

</style>
