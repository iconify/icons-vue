<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="www03acou"/><path class="oanc9p0su"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:mountain-snow-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oanc9p0su {
  d: path("M2 20L7 10L9.5 13L14.0349 4L22 20ZM10.481 11.0531C10.9498 10.8292 12.2136 10.0874 13.5 10.5C15.835 11.249 16.1204 10.1424 16.8571 9.6692");
}

.www03acou {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M1.1056 19.5528L6.1056 9.5528C6.275 9.214 6.6212 9 7 9C7.2968 9 7.5782 9.1318 7.7682 9.3598L9.2927 11.1892L13.1419 3.55C13.3118 3.2128 13.6572 3 14.0349 3C14.4143 3 14.761 3.2147 14.9301 3.5543L22.8952 19.5543C22.9641 19.6928 23 19.8453 23 20C23 20.5523 22.5523 21 22 21L2 21C1.4477 21 1 20.5523 1 20C1 19.8448 1.0361 19.6916 1.1056 19.5528Z");
  stroke: none;
}

</style>
