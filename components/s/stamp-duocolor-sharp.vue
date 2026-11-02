<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qkeh7ubxs"/><path class="jk-wm0uju"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:stamp-duocolor-sharp" /></template>
<style>
.jk-wm0uju {
  d: path("M4 12h16v5H4Zm1 9h14");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qkeh7ubxs {
  stroke-opacity: 0.4;
  d: path("M10 12V8a2.828 2.828 0 1 1 4 0v4");
}

</style>
