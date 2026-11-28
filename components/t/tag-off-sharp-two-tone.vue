<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="kld17kbnu"/><path class="fwziqygkv"/><path clip-rule="evenodd" class="z5tvdhbcs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:tag-off-sharp-two-tone" /></template>
<style>
.fwziqygkv {
  d: path("M16.801 7.199L22 12.828L12.828 22L7.199 16.801M22.293 1.707L1.707 22.293");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.kld17kbnu {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6.491 17.509L12.15 22.735C12.544 23.099 13.156 23.087 13.535 22.707L22.707 13.535C23.087 13.156 23.099 12.544 22.735 12.15L17.509 6.491L6.491 17.509ZM15.753 4.59L12.735 1.322C12.545 1.117 12.279 1 12 1H2C1.448 1 1 1.448 1 2V12C1 12.279 1.117 12.545 1.322 12.735L4.59 15.753L15.753 4.59Z");
  stroke: none;
}

.z5tvdhbcs {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.5 8C9.5 8.828 8.828 9.5 8 9.5C7.172 9.5 6.5 8.828 6.5 8C6.5 7.172 7.172 6.5 8 6.5C8.828 6.5 9.5 7.172 9.5 8Z");
  stroke: none;
}

</style>
