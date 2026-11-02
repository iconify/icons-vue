<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ea61czo5c"/><path class="w-hsj3b8v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:subway-duocolor" /></template>
<style>
.ea61czo5c {
  stroke-opacity: 0.4;
  d: path("M3 21v-9a9 9 0 0 1 18 0v9m-11-6h.01M14 15h.01");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.w-hsj3b8v {
  d: path("M7 12a5 5 0 0 1 10 0v5a2 2 0 0 1-2 2H9a2 2 0 0 1-2-2zm3 7l-1 2m5-2l1 2m-8-9h10");
}

</style>
