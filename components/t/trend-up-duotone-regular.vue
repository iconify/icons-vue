<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fg5y2jb8t"/><path class="wy4xfcb9x"/><path class="q0ddccbcl"/><path class="kk-764bgz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:trend-up-duotone-regular" /></template>
<style>
.fg5y2jb8t {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m3 17 6 -6 4 4 8 -8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kk-764bgz {
  d: path("M17 7h4v4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q0ddccbcl {
  d: path("m3 17 6 -6 4 4 8 -8");
}

.wy4xfcb9x {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M17 7h4v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
