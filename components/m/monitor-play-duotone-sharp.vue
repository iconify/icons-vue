<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="o42c4u5zt"/><path class="e71wle9zp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:monitor-play-duotone-sharp" /></template>
<style>
.e71wle9zp {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 4h16v13H4Zm5 16h6M10 7l5 3.5l-5 3.5Z");
}

.ft5dv1b6b {
  fill: none;
}

.o42c4u5zt {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M20 4v13H4V4Z");
}

</style>
