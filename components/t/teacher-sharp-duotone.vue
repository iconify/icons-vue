<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="abkd-1bcx"/><path class="fp7155v2h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:teacher-sharp-duotone" /></template>
<style>
.abkd-1bcx {
  stroke-opacity: 0.4;
  d: path("M9 6.5917L9 2L22 2L22 15L12.1235 15M12 6.5L19 6.5M13 10.5L19 10.5");
}

.fp7155v2h {
  fill: currentColor;
  d: path("M10.5 12C10.5 13.933 8.933 15.5 7 15.5C5.067 15.5 3.5 13.933 3.5 12C3.5 10.067 5.067 8.5 7 8.5C8.933 8.5 10.5 10.067 10.5 12ZM1 21.5C1 19.2909 2.7909 17.5 5 17.5L9 17.5C11.2091 17.5 13 19.2909 13 21.5L13 22C13 22.5523 12.5523 23 12 23L2 23C1.4477 23 1 22.5523 1 22Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
