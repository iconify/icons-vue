<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wk6aolb1y"/><path class="x9uh-0-ei"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:stethoscope-fill" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wk6aolb1y {
  fill: currentColor;
  d: path("M23 10C23 11.6569 21.6569 13 20 13C18.3431 13 17 11.6569 17 10C17 8.3431 18.3431 7 20 7C21.6569 7 23 8.3431 23 10Z");
  stroke: none;
}

.x9uh-0-ei {
  d: path("M8 15C2.9955 15 1.7856 8.2335 2.0294 4.623C2.0936 3.672 2.8935 3 3.8097 3L5.117 3M8 15C13.0045 15 14.2144 8.2335 13.9706 4.623C13.9064 3.672 13.1065 3 12.1903 3L10.883 3M20 12L20 15C20 18.3137 17.3137 21 14 21C10.6863 21 8 18.3137 8 15");
}

</style>
