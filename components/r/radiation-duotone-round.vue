<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ctjnh9ryb"/><path class="dn_yk0bps"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:radiation-duotone-round" /></template>
<style>
.ctjnh9ryb {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M10 8a4.22 4.22 0 0 0-2 4H3a8.97 8.97 0 0 1 5-8Zm6 4a4.22 4.22 0 0 0-2-4l2-4a8.97 8.97 0 0 1 5 8Zm-6 4a4.47 4.47 0 0 0 4 0l2 4a8.94 8.94 0 0 1-8 0Z");
}

.dn_yk0bps {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16 12h5a8.97 8.97 0 0 0-5-8l-2 4a4.22 4.22 0 0 1 2 4m-6-4L8 4a8.97 8.97 0 0 0-5 8h5a4.22 4.22 0 0 1 2-4m0 8l-2 4a8.94 8.94 0 0 0 8 0l-2-4a4.47 4.47 0 0 1-4 0m2-4h.01");
}

.ft5dv1b6b {
  fill: none;
}

</style>
