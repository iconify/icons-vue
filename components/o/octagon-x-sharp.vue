<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="up15_y9jb"/><path class="w5-w_sbbd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:octagon-x-sharp" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.up15_y9jb {
  d: path("M3 15.6L3 8.4L8.4 3L15.6 3L21 8.4L21 15.6L15.6 21L8.4 21L3 15.6Z");
}

.w5-w_sbbd {
  d: path("M8.7071 8.7071L15.2929 15.2929M15.2929 8.7071L8.7071 15.2929");
}

</style>
