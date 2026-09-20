<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="duz1sfbva"/><path class="wloabnb9u"/><path class="w2_t-sslc"/><path class="kg5ylpb0c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pen-duotone-regular" /></template>
<style>
.duz1sfbva {
  fill: currentColor;
  d: path("m8 16 9 -9 3 3 -9 9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.kg5ylpb0c {
  d: path("M8 16v3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.w2_t-sslc {
  d: path("m8 16 -3 3h6");
}

.wloabnb9u {
  d: path("m8 16 9 -9 3 3 -9 9Z");
}

</style>
