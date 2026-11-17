<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="p6y0vdbui"/><path class="iwh2v7crp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shapes-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.iwh2v7crp {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 15h6v6H3Zm10 2a4 4 0 1 0 8 0a4 4 0 0 0-8 0M8 4l4 6H4Z");
}

.p6y0vdbui {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m8 4l4 6H4Zm5 13a4 4 0 1 1 8 0a4 4 0 0 1-8 0M3 15h6v6H3Z");
}

</style>
