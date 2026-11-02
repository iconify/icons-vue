<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="xy8mi4e0x"/><path class="bdniwqb0w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:motorbike-duotone" /></template>
<style>
.bdniwqb0w {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 18a3 3 0 0 1 6 0m0 0a3 3 0 0 1-6 0m12 0a3 3 0 0 1 6 0m0 0a3 3 0 0 1-6 0m-6 0h2a1 1 0 0 0 1-1a5 5 0 0 1 5-5a1 1 0 0 0 1-1m0 4V8a2 2 0 0 0-2-2M3 10l6 2a2 2 0 0 1 2-2h1a2 2 0 0 1 2 2v1");
}

.ft5dv1b6b {
  fill: none;
}

.xy8mi4e0x {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M11 9h1a3 3 0 0 1 3 3v1a.998.998 0 0 1-1.196.981l-5-1A1 1 0 0 1 8 12a3 3 0 0 1 .236-1.168c.15-.357.369-.68.643-.953A3 3 0 0 1 11 9m-8.685 7.443a4.001 4.001 0 0 1 7.37 3.114a4.001 4.001 0 0 1-7.37-3.114m12 0a4.001 4.001 0 0 1 7.37 3.114a4.001 4.001 0 0 1-7.37-3.114M5 18a1 1 0 1 0 2 0a1 1 0 0 0-2 0m12 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

</style>
