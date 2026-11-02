<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tqffmp7ti"/><path class="gw6y7cc0t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-dashed-close-duocolor" /></template>
<style>
.gw6y7cc0t {
  d: path("M3 6V5a2 2 0 0 1 2-2h1m12 0h1a2 2 0 0 1 2 2v1m0 12v1a2 2 0 0 1-2 2h-1M6 21H5a2 2 0 0 1-2-2v-1m7-15h4m7 7v4m-7 7h-4m-7-7v-4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tqffmp7ti {
  stroke-opacity: 0.4;
  d: path("m9 9l6 6m0-6l-6 6");
}

</style>
