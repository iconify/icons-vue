<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="oaky9cbmf"/><path class="jyw82vbqk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:train-fill" /></template>
<style>
.jyw82vbqk {
  d: path("M4 5L2 5M20 5L22 5M7 18L5 22M17 18L19 22");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oaky9cbmf {
  fill: currentColor;
  d: path("M7 1L17 1C19.2091 1 21 2.7909 21 5L21 15C21 17.2091 19.2091 19 17 19L7 19C4.7909 19 3 17.2091 3 15L3 5C3 2.7909 4.7909 1 7 1ZM7 3C5.8954 3 5 3.8954 5 5L5 8L19 8L19 5C19 3.8954 18.1046 3 17 3L7 3ZM10 13.5C10 12.6716 9.3284 12 8.5 12C7.6716 12 7 12.6716 7 13.5C7 14.3284 7.6716 15 8.5 15C9.3284 15 10 14.3284 10 13.5ZM17 13.5C17 12.6716 16.3284 12 15.5 12C14.6716 12 14 12.6716 14 13.5C14 14.3284 14.6716 15 15.5 15C16.3284 15 17 14.3284 17 13.5Z");
  stroke: none;
}

</style>
