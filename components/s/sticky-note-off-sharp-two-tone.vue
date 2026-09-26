<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="zgnmhybub"/><path class="b8rq8pb_n"/><path class="i6hnv8b0r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sticky-note-off-sharp-two-tone" /></template>
<style>
.b8rq8pb_n {
  stroke-opacity: 0.4;
  d: path("M7.6569 3L15 3L21 9L21 16.3431M15 3L15 9L21 9");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.i6hnv8b0r {
  d: path("M3 3L3 21L21 21M1.7071 1.7071L22.2929 22.2929");
}

.zgnmhybub {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21.7071 21.7071C21.5196 21.8946 21.2652 22 21 22L3 22C2.4477 22 2 21.5523 2 21L2 3C2 2.7348 2.1054 2.4804 2.2929 2.2929L21.7071 21.7071Z");
  stroke: none;
}

</style>
