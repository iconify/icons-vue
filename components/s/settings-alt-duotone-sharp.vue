<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="a8i3hdckq"/><path class="ldh_orbgg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:settings-alt-duotone-sharp" /></template>
<style>
.a8i3hdckq {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M21 7v10a1 1 0 0 1-.553.894l-8 4a1 1 0 0 1-.894 0l-8-4A1 1 0 0 1 3 17V7c0-.379.214-.725.553-.894l8-4a1 1 0 0 1 .894 0l8 4A1 1 0 0 1 21 7M9 12a3 3 0 1 0 6 0a3 3 0 0 0-6 0");
}

.ft5dv1b6b {
  fill: none;
}

.ldh_orbgg {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M20 12v5l-8 4l-8-4V7l8-4l8 4zM9 12a3 3 0 1 0 6 0a3 3 0 0 0-6 0");
}

</style>
