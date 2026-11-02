<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="mvwb79mxs"/><path class="gxhf66gwd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:thumbs-up-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gxhf66gwd {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 10a4 4 0 0 0 4-4V5a2 2 0 1 1 4 0v3a2 2 0 0 0 2 2h2a2 2 0 0 1 2 2v2l-2 6c-.2.597-1.005 1-2 1H9a2 2 0 0 1-2-2m0-9H5a2 2 0 0 0-2 2v7a2 2 0 1 0 4 0z");
}

.mvwb79mxs {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M10 6V5a3 3 0 1 1 6 0v3a.997.997 0 0 0 1 1h2a3 3 0 0 1 3 3v2a1 1 0 0 1-.051.316l-2 6c-.196.586-.66 1.031-1.203 1.302c-.541.271-1.145.382-1.746.382H9c-.74 0-1.45-.27-2-.764a3 3 0 0 1-3.225.502A3 3 0 0 1 2 19v-7a3 3 0 0 1 3-3h2a3 3 0 0 0 3-3");
}

</style>
