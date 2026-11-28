<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="a8trpwbou"/><path class="evihppbgj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:search-activity-duotone" /></template>
<style>
.a8trpwbou {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M15.6569 15.6569C14.2102 17.1035 12.2089 18 10 18C5.5817 18 2 14.4183 2 10C2 5.5817 5.5817 2 10 2C14.4183 2 18 5.5817 18 10C18 12.2089 17.1035 14.2102 15.6569 15.6569Z");
  stroke: none;
}

.evihppbgj {
  d: path("M5 10L7.5 10L9 7.5L11 12.5L12.5 10L15 10M15 15L21 21");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
