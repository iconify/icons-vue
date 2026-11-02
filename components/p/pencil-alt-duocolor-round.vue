<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="w-h6ynb5v"/><path class="liwe7bcrx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pencil-alt-duocolor-round" /></template>
<style>
.liwe7bcrx {
  d: path("M4 16L14 6a2.828 2.828 0 1 1 4 4L8 20");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.w-h6ynb5v {
  stroke-opacity: 0.4;
  d: path("M8 20H4v-4");
}

</style>
