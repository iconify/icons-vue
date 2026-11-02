<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="im5aihf0i"/><path class="yhdsbe0jv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:playlist-duocolor" /></template>
<style>
.im5aihf0i {
  stroke-opacity: 0.4;
  d: path("M15 11v6c0 .23.54.23 1 0l4-2a1.118 1.118 0 0 0 0-2l-4-2c-.46-.23-1-.23-1 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.yhdsbe0jv {
  d: path("M3 6h18M3 12h8m-8 6h8");
}

</style>
