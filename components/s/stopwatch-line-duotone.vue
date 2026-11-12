<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="p7p5oub5r"/><path class="pxm7_12cz"/><path class="u8gkuv4uz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:stopwatch-line-duotone" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p7p5oub5r {
  d: path("M21 13C21 17.9706 16.9706 22 12 22C7.02944 22 3 17.9706 3 13C3 8.02944 7.02944 4 12 4C16.9706 4 21 8.02944 21 13Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.pxm7_12cz {
  stroke-linejoin: round;
  d: path("M12 13V9");
}

.u8gkuv4uz {
  d: path("M10 2H14");
}

</style>
