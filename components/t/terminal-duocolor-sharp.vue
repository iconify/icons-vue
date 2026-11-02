<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="uqtej22cr"/><path class="r21jxhxfq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:terminal-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r21jxhxfq {
  d: path("M3 5h18v14H3Z");
}

.uqtej22cr {
  stroke-opacity: 0.4;
  d: path("m7 9l3 3l-3 3m6 0h4");
}

</style>
