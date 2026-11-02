<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="a-7__ob0f"/><path class="o9ouznb3y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tag-duocolor-sharp" /></template>
<style>
.a-7__ob0f {
  stroke-opacity: 0.4;
  d: path("M8 9a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o9ouznb3y {
  d: path("M8 4h4l8 8l-8 8l-8-8V4z");
}

</style>
