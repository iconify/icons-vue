<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fg9f2g5hk"/><path class="lw6t35brr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:panel-top-duocolor-sharp" /></template>
<style>
.fg9f2g5hk {
  stroke-opacity: 0.4;
  d: path("M4 9h16");
}

.lw6t35brr {
  d: path("M4 4h16v16H4Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
