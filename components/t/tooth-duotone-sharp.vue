<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="i-51vky1v"/><path class="l-nbotb_e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tooth-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.i-51vky1v {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M12 2.764C12.901 2.215 13.955 2 15 2a4.995 4.995 0 0 1 5 5a37 37 0 0 1-.161 3.662c-.164 1.634-.524 3.241-.688 4.875A35 35 0 0 0 19 19a3.001 3.001 0 0 1-6 0v-1a1 1 0 0 0-2 0v1a3 3 0 0 1-6 0a35 35 0 0 0-.151-3.463c-.164-1.634-.524-3.241-.688-4.875A37 37 0 0 1 4 7a4.995 4.995 0 0 1 5-5c1.045 0 2.099.215 3 .764");
}

.l-nbotb_e {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 4c-.8-.7-1.8-1-3-1a4 4 0 0 0-4 4c0 6 1 6 1 12a2 2 0 1 0 4 0v-1a2 2 0 1 1 4 0v1a2 2 0 1 0 4 0c0-6 1-6 1-12a4 4 0 0 0-4-4c-1.2 0-2.2.3-3 1");
}

</style>
