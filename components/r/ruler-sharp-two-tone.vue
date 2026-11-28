<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="o_5gcqdfk"/><path class="daii_5bpw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:ruler-sharp-two-tone" /></template>
<style>
.daii_5bpw {
  d: path("M4.929 13.414L8.465 16.95M7.757 10.586L10.232 13.061M10.586 7.757L14.121 11.293M13.414 4.929L15.889 7.404M2 16.343L16.343 2L22 7.657L7.657 22L2 16.343Z");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o_5gcqdfk {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M1.293 17.05C1.105 16.863 1 16.608 1 16.343C1 16.078 1.105 15.824 1.293 15.636L15.636 1.293C15.824 1.105 16.078 1 16.343 1C16.608 1 16.863 1.105 17.05 1.293L22.707 6.95C22.895 7.137 23 7.392 23 7.657C23 7.922 22.895 8.176 22.707 8.364L8.364 22.707C8.176 22.895 7.922 23 7.657 23C7.392 23 7.137 22.895 6.95 22.707L1.293 17.05Z");
  stroke: none;
}

</style>
