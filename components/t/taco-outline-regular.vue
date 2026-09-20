<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zc40vp7yl"/><path class="c6yqvq36o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:taco-outline-regular" /></template>
<style>
.c6yqvq36o {
  d: path("M5 11c2 -3 4 -1 7 -3s5 1 7 3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.zc40vp7yl {
  d: path("M4 11c0 5 3 8 8 8s8 -3 8 -8Z");
}

</style>
