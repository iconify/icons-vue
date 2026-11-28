<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ahihb4qon"/><path class="ncum3bb2t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:piano-two-tone" /></template>
<style>
.ahihb4qon {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 3L19 3C21.2092 3 23 4.7908 23 7L23 17C23 19.2092 21.2092 21 19 21L5 21C2.7908 21 1 19.2092 1 17L1 7C1 4.7908 2.7908 3 5 3Z");
  stroke: none;
}

.ncum3bb2t {
  d: path("M5 4L19 4C20.6569 4 22 5.3431 22 7L22 17C22 18.6569 20.6569 20 19 20L5 20C3.3431 20 2 18.6569 2 17L2 7C2 5.3431 3.3431 4 5 4ZM6 4V12C6 12.5523 6.4477 13 7 13H9C9.5523 13 10 12.5523 10 12V4M8 13V20M14 4V12C14 12.5523 14.4477 13 15 13H17C17.5523 13 18 12.5523 18 12V4M16 13V20");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
