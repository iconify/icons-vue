<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ugww-4jxa"/><path class="tl2b-zblk"/><path class="i3nsbzblu"/><path class="rg7tj2b_x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:model-size-duotone-regular" /></template>
<style>
.i3nsbzblu {
  d: path("m10 3 7 7 -7 7 -7 -7Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rg7tj2b_x {
  d: path("m18 14 3.5 3.5L18 21l-3.5 -3.5Z");
}

.tl2b-zblk {
  fill: currentColor;
  d: path("m18 14 3.5 3.5L18 21l-3.5 -3.5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ugww-4jxa {
  fill: currentColor;
  d: path("m10 3 7 7 -7 7 -7 -7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
