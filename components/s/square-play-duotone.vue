<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="u4yt2i7xs"/><path class="k1uktu2et"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-play-duotone" /></template>
<style>
.k1uktu2et {
  d: path("M8.962734 9.105541C8.962734 8.320105 9.826684 7.841262 10.492732 8.257542L15.802266 11.576001C16.1156 11.771835 16.1156 12.228165 15.802266 12.423999L10.492732 15.742458C9.826684 16.158738 8.962734 15.679895 8.962734 14.894459Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.u4yt2i7xs {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 6C2 3.790861 3.790861 2 6 2L18 2C20.209139 2 22 3.790861 22 6L22 18C22 20.209139 20.209139 22 18 22L6 22C3.790861 22 2 20.209139 2 18Z");
  stroke: none;
}

</style>
