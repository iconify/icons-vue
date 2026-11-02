<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="vel6goxzz"/><path class="uo9n2ybdt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:navigation-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.uo9n2ybdt {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m12 6l9 3l-8 4l-4 8L3 3z");
}

.vel6goxzz {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m21 9l-8 4l-4 8L3 3Z");
}

</style>
