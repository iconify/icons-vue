<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="h2hpwcrhb"/><path class="im48wz0-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:text-size-duocolor" /></template>
<style>
.h2hpwcrhb {
  stroke-opacity: 0.4;
  d: path("M15 11h6m-3 0v8");
}

.im48wz0-s {
  d: path("M3 5h10M8 5v14");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
