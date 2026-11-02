<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jf-xq3dua"/><path class="hmy55ry8s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:signal-medium-duocolor" /></template>
<style>
.hmy55ry8s {
  d: path("M6 20v-4m4 4v-8m4 8V8");
}

.jf-xq3dua {
  stroke-opacity: 0.4;
  d: path("M18 20h.01");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
