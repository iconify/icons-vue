<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="p0lunj6wu"/><path class="o_bt3mbrk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-code" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o_bt3mbrk {
  d: path("M10 8.5L7 12L10 15.5M14 8.5L17 12L14 15.5");
}

.p0lunj6wu {
  d: path("M6 3H18C19.6569 3 21 4.3432 21 6V18C21 19.6569 19.6569 21 18 21H6C4.3431 21 3 19.6569 3 18V6C3 4.3432 4.3431 3 6 3Z");
}

</style>
