<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="oxp4-8bii"/><path class="wj_m9rb7i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:tag-off-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oxp4-8bii {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6.554 17.566L12.15 22.735C12.544 23.099 13.156 23.087 13.535 22.707L22.707 13.535C23.087 13.156 23.099 12.544 22.735 12.15L17.566 6.554L6.554 17.566ZM15.753 4.59L12.735 1.322C12.545 1.117 12.279 1 12 1H2C1.448 1 1 1.448 1 2V12C1 12.279 1.117 12.545 1.322 12.735L4.59 15.753L15.753 4.59ZM9.5 8C9.5 8.828 8.828 9.5 8 9.5C7.172 9.5 6.5 8.828 6.5 8C6.5 7.172 7.172 6.5 8 6.5C8.828 6.5 9.5 7.172 9.5 8Z");
  stroke: none;
}

.wj_m9rb7i {
  d: path("M22.293 1.707L1.707 22.293");
}

</style>
