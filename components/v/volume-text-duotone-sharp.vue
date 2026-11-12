<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="wwfjbhb8j"/><path class="l74rlon_t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:volume-text-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.l74rlon_t {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 10h3l5-5v14l-5-5h-3zM3 9h6M6 9v6");
}

.wwfjbhb8j {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m15.586 9l4.707-4.707A1 1 0 0 1 22 5v14a1.002 1.002 0 0 1-1.707.707L15.586 15H13a1 1 0 0 1-1-1v-4a1 1 0 0 1 1-1Z");
}

</style>
