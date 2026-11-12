<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wj9xfdcvp"/><path class="iryhk-bnp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:table-transpose-duocolor-sharp" /></template>
<style>
.iryhk-bnp {
  d: path("M11 3h10v4H11Zm-8 8h4v10H3Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wj9xfdcvp {
  stroke-opacity: 0.4;
  d: path("M18 19h-4v-4m0 4l6-6");
}

</style>
