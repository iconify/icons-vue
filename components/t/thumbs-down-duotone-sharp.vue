<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="j7_desbdl"/><path class="rkmkktb6a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:thumbs-down-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.j7_desbdl {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M7 14H3V3h16l2 7v4h-6v5a2 2 0 1 1-4 0v-1a4 4 0 0 0-4-4");
}

.rkmkktb6a {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 14a4 4 0 0 1 4 4v1a2 2 0 1 0 4 0v-5h6v-4l-2-7H7m0 11H3V3h4z");
}

</style>
