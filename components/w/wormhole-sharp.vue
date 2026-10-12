<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="hue5ftoat"/><path class="of2c3hfex"/><path class="y2zq3gb5i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:wormhole-sharp" /></template>
<style>
.hue5ftoat {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 3a2 9 0 1 0 0 18a2 9 0 1 0 0-18Zm6.5 4a1.5 5 0 1 0 0 10a1.5 5 0 1 0 0-10Zm5.5 2.5a1 2.5 0 1 0 0 5a1 2.5 0 1 0 0-5Z");
}

.of2c3hfex {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 3q7 4.75 12 6.5M4.75 21q7-4.75 12-6.5");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.y2zq3gb5i {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M21 12h.01");
}

</style>
