<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="knt-4n5fd"/><path class="zu5txb9-o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:running-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.knt-4n5fd {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M14 5a1 1 0 1 1 2 0a1 1 0 0 1-2 0");
}

.zu5txb9-o {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m12 9l-2 5l4 3v4m-4-7l-2 4l-4-1m3-5l1-3h4l3 3h5m-6-7a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

</style>
