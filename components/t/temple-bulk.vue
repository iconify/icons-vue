<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="mxyk0mbeg"/><path class="p84hi2vnn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:temple-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.mxyk0mbeg {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 13a4 4 0 0 1-4-4a1 1 0 0 1 1-1a9.8 9.8 0 0 0 3.063-.466A8 8 0 0 0 8.4 6.325a7.7 7.7 0 0 0 1.66-1.701a7.4 7.4 0 0 0 .991-1.94a1.001 1.001 0 0 1 1.898 0A7.6 7.6 0 0 0 15.6 6.325C17.158 7.493 19.069 8 21 8a1 1 0 0 1 1 1a3.98 3.98 0 0 1-1.172 2.828A3.98 3.98 0 0 1 18 13Z");
}

.p84hi2vnn {
  d: path("M10 22H3a1 1 0 0 1 0-2h2v-8a1 1 0 0 1 2 0v8h2v-2a3 3 0 1 1 6 0v2h2v-8a1 1 0 0 1 2 0v8h2a1 1 0 0 1 0 2h-7a1 1 0 0 1-1-1v-3a1 1 0 0 0-2 0v3a1 1 0 0 1-1 1");
}

</style>
