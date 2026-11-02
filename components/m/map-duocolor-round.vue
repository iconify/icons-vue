<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cf8r2lbua"/><path class="wvto_bn2j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:map-duocolor-round" /></template>
<style>
.cf8r2lbua {
  stroke-opacity: 0.4;
  d: path("M9 3v15m6-12v15");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wvto_bn2j {
  d: path("m9 3l6 3l2-1c1.838-.919 4 .162 4 2v9c0 1.226-.774 2.387-2 3l-4 2l-6-3l-2 1c-1.838.919-4-.162-4-2V8c0-1.226.774-2.387 2-3z");
}

</style>
