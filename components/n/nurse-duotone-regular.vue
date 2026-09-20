<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tzdfp4-do"/><path class="ufzn_r3vk"/><path class="m1oey3b_j"/><path class="m-9jjacoy"/><path class="w5i79a2na"/><path class="wy2n5sbyh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:nurse-duotone-regular" /></template>
<style>
.m-9jjacoy {
  d: path("M8 6V3h8v3");
}

.m1oey3b_j {
  d: path("M5.4 17a6.6 6.6 0 0 1 13.2 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tzdfp4-do {
  fill: currentColor;
  d: path("M9 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ufzn_r3vk {
  d: path("M9 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.w5i79a2na {
  d: path("M12 14v4");
}

.wy2n5sbyh {
  d: path("M10 16h4");
}

</style>
