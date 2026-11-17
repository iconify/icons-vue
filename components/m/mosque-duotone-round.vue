<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="v3d_vpb3l"/><path class="xu1rj-vna"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mosque-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.v3d_vpb3l {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M8 13a4 4 0 0 1 8 0h4v4a4 4 0 0 1-4 4H8a4 4 0 0 1-4-4v-4Z");
}

.xu1rj-vna {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 13h16v4a4 4 0 0 1-4 4H8a4 4 0 0 1-4-4zm4 0a4 4 0 1 1 8 0M4 13V9m16 4V9M4 6c1 1.5 1 2 1 3H3c0-1 0-1.5 1-3m16 0c1 1.5 1 2 1 3h-2c0-1 0-1.5 1-3M10 21v-2a2 2 0 1 1 4 0v2M10.586 2.586a2 2 0 1 0 2.828 2.828M12 6v3");
}

</style>
