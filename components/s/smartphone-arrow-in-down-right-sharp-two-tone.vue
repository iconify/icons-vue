<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ctkwnzbjp"/><path class="c9ntyqb6k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:smartphone-arrow-in-down-right-sharp-two-tone" /></template>
<style>
.c9ntyqb6k {
  d: path("M19 13L19 2L5 2L5 22L10 22M14.5 6L9.5 6M13.7071 16.7071L18.8536 21.8536M12 22L19 22L19 15");
}

.ctkwnzbjp {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20 2L20 12C20 12.5523 19.5523 13 19 13L10 13L10 22C10 22.5523 9.5523 23 9 23C6.2386 23 4 20.7614 4 18L4 2C4 1.4477 4.4477 1 5 1L19 1C19.5523 1 20 1.4477 20 2Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
