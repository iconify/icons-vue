<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="jiyipbb-d"/><path clip-rule="evenodd" class="z5tvdhbcs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:tag-off-sharp" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.jiyipbb-d {
  d: path("M4.993 14.764L4.258 14.085L2 12V2H12L14.085 4.258L14.764 4.993M16.801 7.199L22 12.828L12.828 22L7.199 16.801M22.293 1.707L1.707 22.293");
}

.z5tvdhbcs {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.5 8C9.5 8.828 8.828 9.5 8 9.5C7.172 9.5 6.5 8.828 6.5 8C6.5 7.172 7.172 6.5 8 6.5C8.828 6.5 9.5 7.172 9.5 8Z");
  stroke: none;
}

</style>
