<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cr7e85qlf"/><path class="vlattublo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:toolbox-duocolor-sharp" /></template>
<style>
.cr7e85qlf {
  stroke-opacity: 0.4;
  d: path("M9 8V4h6v4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vlattublo {
  d: path("M3 8h18v12H3Zm0 6h18M8 12v4m8-4v4");
}

</style>
