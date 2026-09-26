<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="l1ojs5toy"/><path class="eh_8t3brt"/><path class="d9f73pbit"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:tag-horizontal-end-percent-sharp-duotone" /></template>
<style>
.d9f73pbit {
  fill: currentColor;
  d: path("M11.25 8.5C11.25 9.3284 11.9216 10 12.75 10C13.5784 10 14.25 9.3284 14.25 8.5C14.25 7.6716 13.5784 7 12.75 7C11.9216 7 11.25 7.6716 11.25 8.5ZM5.25 15.5C5.25 16.3284 5.9216 17 6.75 17C7.5784 17 8.25 16.3284 8.25 15.5C8.25 14.6716 7.5784 14 6.75 14C5.9216 14 5.25 14.6716 5.25 15.5Z");
  stroke: none;
}

.eh_8t3brt {
  d: path("M13.0429 15.2929L6.4571 8.7071");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.l1ojs5toy {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 3C1.4477 3 1 3.4477 1 4L1 20C1 20.5523 1.4477 21 2 21L14.8284 21C15.1126 21 15.3833 20.8791 15.573 20.6675L22.7446 12.6675C23.0851 12.2876 23.0851 11.7124 22.7446 11.3325L15.573 3.3325C15.3833 3.1209 15.1126 3 14.8284 3L2 3Z");
  stroke: none;
}

</style>
