<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="w12kb4b5r"/><path class="gf6u1ib1a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:ruler-two-tone" /></template>
<style>
.gf6u1ib1a {
  d: path("M4.9289 13.414L7.7574 16.243M7.7574 10.586L9.5251 12.354M10.5858 7.757L13.4142 10.586M13.4142 4.929L15.182 6.697M2.5858 18.586C1.8047 17.805 1.8047 16.538 2.5858 15.757L15.7573 2.586C16.5384 1.805 17.8047 1.805 18.5858 2.586L21.4142 5.414C22.1953 6.195 22.1953 7.462 21.4142 8.243L8.2427 21.414C7.4616 22.195 6.1953 22.195 5.4142 21.414L2.5858 18.586Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.w12kb4b5r {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8.4644 8.464L15.0502 1.879C16.2218 0.707 18.1213 0.707 19.2929 1.879L22.1213 4.707C23.2929 5.879 23.2929 7.778 22.1213 8.95L8.9498 22.121C7.7782 23.293 5.8787 23.293 4.7071 22.121L1.8787 19.293C0.7071 18.121 0.7071 16.222 1.8787 15.05L8.4644 8.464Z");
  stroke: none;
}

</style>
