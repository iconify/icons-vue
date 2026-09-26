<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="z095i3bvc"/><path class="hiwtpra8u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:paintbrush-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.hiwtpra8u {
  d: path("M5 12L19 12L19 16L13.8 16L15 22L9 22L9.5 19.5L10.2 16L5 16ZM10 1L10 7M14 1L14 9");
}

.z095i3bvc {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  fill-rule: evenodd;
  d: path("M12 1L18 1C18.5523 1 19 1.4477 19 2L19 11L19 11C19.5523 11 20 11.4477 20 12L20 16C20 16.5523 19.5523 17 19 17L15.0198 17L15.9806 21.8039C15.9935 21.8685 16 21.9341 16 22C16 22.5523 15.5523 23 15 23L9 23C8.4477 23 8 22.5523 8 22C8 21.9341 8.0065 21.8685 8.0194 21.8039L8.5194 19.3039L8.9802 17L5 17C4.4477 17 4 16.5523 4 16L4 12C4 11.4477 4.4477 11 5 11L5 11L5 2C5 1.4477 5.4477 1 6 1L12 1ZM12 13L6 13L6 15L10.2 15C10.4996 15 10.7834 15.1343 10.9733 15.366C11.1633 15.5977 11.2393 15.9023 11.1806 16.1961L10.2198 21L13.7802 21L12.8194 16.1961C12.7607 15.9023 12.8367 15.5977 13.0267 15.366C13.2166 15.1343 13.5004 15 13.8 15L18 15L18 13L12 13Z");
  stroke: none;
}

</style>
