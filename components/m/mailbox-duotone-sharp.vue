<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="hpwrvsx3e"/><path class="e7z244b_y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mailbox-duotone-sharp" /></template>
<style>
.e7z244b_y {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 9h14v12H3v-8a4 4 0 0 1 4-4m0 0a4 4 0 0 1 4 4v8m6-12V3h4");
}

.ft5dv1b6b {
  fill: none;
}

.hpwrvsx3e {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M7 8h14a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1v-8a5 5 0 0 1 5-5");
}

</style>
