<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="d8yrrybov"/><path class="t62u472kc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:tv-duotone" /></template>
<style>
.d8yrrybov {
  stroke-opacity: 0.4;
  d: path("M8 3L12 8L16 3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.t62u472kc {
  fill: currentColor;
  d: path("M1 11C1 8.7909 2.7909 7 5 7L19 7C21.2091 7 23 8.7909 23 11L23 18C23 20.2091 21.2091 22 19 22L5 22C2.7909 22 1 20.2091 1 18L1 11Z");
  stroke: none;
}

</style>
