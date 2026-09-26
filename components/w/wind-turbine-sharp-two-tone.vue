<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="iq62dem-e"/><path class="r_s164jdj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:wind-turbine-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.iq62dem-e {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M15.5 9.5C15.5 11.433 13.933 13 12 13C10.067 13 8.5 11.433 8.5 9.5C8.5 7.567 10.067 6 12 6C13.933 6 15.5 7.567 15.5 9.5Z");
  stroke: none;
}

.r_s164jdj {
  d: path("M12 7L12 1M14.1651 10.75L18.9952 13.5387M9.8349 10.75L5.0048 13.5387M12 12L12 22M4 22L20 22M15.5005 2.283L16 2.5718C18.4752 4.0009 20 6.6419 20 9.5C20 9.5146 20 9.5292 19.9999 9.5438L19.9931 10.537M4.0069 10.537L4.0001 9.5438C4 9.5292 4 9.5146 4 9.5C4 6.6419 5.5248 4.0009 8 2.5718L8.4995 2.283M14.5 9.5C14.5 10.8807 13.3807 12 12 12C10.6193 12 9.5 10.8807 9.5 9.5C9.5 8.1193 10.6193 7 12 7C13.3807 7 14.5 8.1193 14.5 9.5Z");
}

</style>
