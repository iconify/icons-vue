<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="tsqm_4b-a"/><path class="a-spkmypt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:temple-duotone-sharp" /></template>
<style>
.a-spkmypt {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 21h7m4 0h7M6 12h12a3 3 0 0 0 3-3c-5 0-8-3-9-6c-1 3-4 6-9 6a3 3 0 0 0 3 3m0 9v-9m12 9v-9m-8 9v-3a2 2 0 1 1 4 0v3");
}

.ft5dv1b6b {
  fill: none;
}

.tsqm_4b-a {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M18 13H6a4 4 0 0 1-4-4a1 1 0 0 1 1-1a9.8 9.8 0 0 0 3.063-.466A8 8 0 0 0 8.4 6.325a7.7 7.7 0 0 0 1.66-1.701a7.4 7.4 0 0 0 .991-1.94a1.001 1.001 0 0 1 1.898 0A7.6 7.6 0 0 0 15.6 6.325C17.158 7.493 19.069 8 21 8a1 1 0 0 1 1 1a3.98 3.98 0 0 1-1.172 2.828A3.98 3.98 0 0 1 18 13");
}

</style>
