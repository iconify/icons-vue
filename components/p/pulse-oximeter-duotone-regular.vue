<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wn2nolguj"/><path class="j5oarkb0z"/><path class="tea8p3bbk"/><path class="cnhldwb8g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pulse-oximeter-duotone-regular" /></template>
<style>
.cnhldwb8g {
  d: path("M6 12h3l2 -2 2 2h3");
}

.j5oarkb0z {
  d: path("M4 8v8h12V8Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tea8p3bbk {
  d: path("M16 12h5");
}

.wn2nolguj {
  fill: currentColor;
  d: path("M4 8v8h12V8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
