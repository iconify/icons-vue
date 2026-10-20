<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ep16y52sl"/><path clip-rule="evenodd" class="vdthl2uri"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:monitor-speaker-sharp-duotone" /></template>
<style>
.ep16y52sl {
  stroke-opacity: 0.4;
  d: path("M9 4L2 4L2 16L9 16M9 20L5 20");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vdthl2uri {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 3L22 3C22.5523 3 23 3.4477 23 4L23 20C23 20.5523 22.5523 21 22 21L12 21C11.4477 21 11 20.5523 11 20L11 4C11 3.4477 11.4477 3 12 3ZM19 15C19 13.8954 18.1046 13 17 13C15.8954 13 15 13.8954 15 15C15 16.1046 15.8954 17 17 17C18.1046 17 19 16.1046 19 15ZM18 8C18 7.4477 17.5523 7 17 7C16.4477 7 16 7.4477 16 8C16 8.5523 16.4477 9 17 9C17.5523 9 18 8.5523 18 8Z");
  stroke: none;
}

</style>
