<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="zukhe8hxu"/><path class="iwh2v7crp"/></g>`;
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

.zukhe8hxu {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M12.832 9.445A1 1 0 0 1 12 11H4a1 1 0 0 1-.832-1.555l4-6a1 1 0 0 1 1.664 0Zm-.439 5.608a5.001 5.001 0 1 1 9.213 3.896a5.001 5.001 0 0 1-9.213-3.896M9 14a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1v-6a1 1 0 0 1 1-1Z");
}

</style>
