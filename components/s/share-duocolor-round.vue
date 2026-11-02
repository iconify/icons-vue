<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dwo5v8b9w"/><path class="lgzg4ib-i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:share-duocolor-round" /></template>
<style>
.dwo5v8b9w {
  stroke-opacity: 0.4;
  d: path("m15 6l-3-3l-3 3m3-3v10");
}

.lgzg4ib-i {
  d: path("M8 10a4 4 0 0 0-4 4v3a4 4 0 0 0 4 4h8a4 4 0 0 0 4-4v-3a4 4 0 0 0-4-4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
