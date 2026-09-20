<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bj7dvbcia"/><path class="c1ganhbov"/><path class="x5t19bc6r"/><path class="v9bmzbkdm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:walking-stick-duotone-regular" /></template>
<style>
.bj7dvbcia {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 21V8a4 4 0 0 1 8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.c1ganhbov {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 21h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.v9bmzbkdm {
  d: path("M5 21h6");
}

.x5t19bc6r {
  d: path("M8 21V8a4 4 0 0 1 8 0");
}

</style>
