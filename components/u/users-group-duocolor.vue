<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jxz1iaboq"/><path class="uq9jp9bdl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:users-group-duocolor" /></template>
<style>
.jxz1iaboq {
  stroke-opacity: 0.4;
  d: path("M8 5a2.236 2.236 0 1 0-2 4m10-4a2.236 2.236 0 1 1 2 4M3 17c0-1.657 1.79-3 4-3m10 0c2.21 0 4 1.343 4 3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.uq9jp9bdl {
  d: path("M9 10a3 3 0 1 0 6 0a3 3 0 0 0-6 0M7 21c0-2.21 2.239-4 5-4s5 1.79 5 4");
}

</style>
