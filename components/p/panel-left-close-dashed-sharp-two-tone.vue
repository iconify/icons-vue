<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="tm7w68bld"/><path class="lzd54cadi"/><path class="zsuk8rbci"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:panel-left-close-dashed-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.lzd54cadi {
  d: path("M9 3L3 3L3 21L9 21L9 3ZM17 3L21 3L21 7M21 17L21 21L17 21M12 3L15 3M12 21L15 21M21 9.5L21 14.5");
}

.tm7w68bld {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 2L21 2C21.5523 2 22 2.4477 22 3L22 21C22 21.5523 21.5523 22 21 22L3 22C2.4477 22 2 21.5523 2 21L2 3C2 2.4477 2.4477 2 3 2ZM3 3L3 21L9 21L9 3Z");
  stroke: none;
}

.zsuk8rbci {
  d: path("M16.2929 8.7071L13 12L16.2929 15.2929");
}

</style>
