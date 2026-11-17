<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jps9vkgsi"/><path class="mi1478fcn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:recharge-duocolor-round" /></template>
<style>
.jps9vkgsi {
  stroke-opacity: 0.4;
  d: path("m13 8l-3 4h4l-3 4");
}

.mi1478fcn {
  d: path("M10.592 3.11a9 9 0 1 1 0 17.78M6.71 19.28a9 9 0 0 1-1.991-1.99M3.11 13.407a9 9 0 0 1 0-2.816M4.719 6.71a9 9 0 0 1 1.99-1.991");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
