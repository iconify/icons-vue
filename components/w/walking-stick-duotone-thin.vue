<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n8snr5b5g"/><path class="y2xvoyirj"/><path class="x5t19bc6r"/><path class="v9bmzbkdm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:walking-stick-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n8snr5b5g {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 21V8a4 4 0 0 1 8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.v9bmzbkdm {
  d: path("M5 21h6");
}

.x5t19bc6r {
  d: path("M8 21V8a4 4 0 0 1 8 0");
}

.y2xvoyirj {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 21h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
