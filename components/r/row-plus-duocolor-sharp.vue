<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jxtldcphh"/><path class="xsbz_u90q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:row-plus-duocolor-sharp" /></template>
<style>
.jxtldcphh {
  stroke-opacity: 0.4;
  d: path("M9 17h6m-3-3v6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xsbz_u90q {
  d: path("M4 4h16v6H4Z");
}

</style>
