<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ypdwp4b9k"/><path class="lo4x8234r"/><path class="sbu14ob8r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-split-bottom-right-duotone" /></template>
<style>
.lo4x8234r {
  fill: currentColor;
  d: path("M12 12H21V18C21 19.657 19.6569 21 18 21H12V12Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sbu14ob8r {
  d: path("M12 21V12H21M3 6C3 4.343 4.3431 3 6 3H18C19.6569 3 21 4.343 21 6V18C21 19.657 19.6569 21 18 21H6C4.3431 21 3 19.657 3 18V6Z");
}

.ypdwp4b9k {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18 2C20.2092 2 22 3.791 22 6V18C22 20.209 20.2092 22 18 22H6C3.7908 22 2 20.209 2 18V6C2 3.791 3.7908 2 6 2H18Z");
  stroke: none;
}

</style>
