<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zrr72d-pi"/><path class="eo5pniblk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:owl-head-duocolor" /></template>
<style>
.eo5pniblk {
  d: path("M4 3c2.5 2 5 3 8 3s5.5-1 8-3c1 2.5 1 5 1 8c0 5.5-4 10-9 10s-9-4.5-9-10c0-3 0-5.5 1-8");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.zrr72d-pi {
  stroke-opacity: 0.4;
  d: path("M6 11a2 2 0 1 0 4 0m0 0a2 2 0 1 0-4 0m8 0a2 2 0 1 0 4 0m0 0a2 2 0 1 0-4 0m-3 4h2l-1 2Z");
}

</style>
