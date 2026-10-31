<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="apztqebvo"/><path class="mnd1l8pxo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:soap-dispenser-droplet-sharp-two-tone" /></template>
<style>
.apztqebvo {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  fill-rule: evenodd;
  d: path("M6 11L6 7C6 6.4477 6.4477 6 7 6L13 6C13.5523 6 14 6.4477 14 7L14 11C14 11.5523 13.5523 12 13 12L7 12C6.4477 12 6 11.5523 6 11ZM20.15 16.2C20.7018 16.9357 21 17.8304 21 18.75C21 21.0972 19.0972 23 16.75 23C14.4028 23 12.5 21.0972 12.5 18.75C12.5 17.8304 12.7983 16.9357 13.35 16.2L15.95 12.7333C16.1389 12.4815 16.4352 12.3333 16.75 12.3333C17.0648 12.3333 17.3611 12.4815 17.55 12.7333L20.15 16.2Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.mnd1l8pxo {
  d: path("M7 11L4 11L4 22L11 22M7 11L7 7L13 7L13 11ZM10 2L10 7M6 2L11.1716 2C12.9826 2 14.7194 2.7194 16 4L16.7071 4.7071M19.35 16.8C19.7719 17.3626 20 18.0468 20 18.75C20 20.5449 18.5449 22 16.75 22C14.9551 22 13.5 20.5449 13.5 18.75C13.5 18.0468 13.7281 17.3626 14.15 16.8L16.75 13.3333Z");
}

</style>
