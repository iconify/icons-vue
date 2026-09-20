<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zirb-hbnv"/><path class="x8ux9pb9v"/><path class="dvobmj5db"/><path class="otd842a5m"/><path class="x6ykmmben"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:share-outline-regular" /></template>
<style>
.dvobmj5db {
  d: path("M14 20a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.otd842a5m {
  d: path("m9.5 10.5 5 -5");
}

.x6ykmmben {
  d: path("m9.5 13.5 5 5");
}

.x8ux9pb9v {
  d: path("M14 4a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.zirb-hbnv {
  d: path("M6 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
