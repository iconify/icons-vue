<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="i166q8fgq"/><path class="j9_sc9s1l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pizza-duocolor-round" /></template>
<style>
.i166q8fgq {
  stroke-opacity: 0.4;
  d: path("M12 10h.01M11 13h.01");
}

.j9_sc9s1l {
  d: path("m4 19l8-16l8 16a17 17 0 0 1-16 0m14-4a12.53 12.53 0 0 1-12 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
