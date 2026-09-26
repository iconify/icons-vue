<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ml1zq97yw"/><path class="zuv35owmt"/><path class="pndcq9b5c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:panel-left-open-dashed-duotone" /></template>
<style>
.ml1zq97yw {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 2L9 2C9.5523 2 10 2.4477 10 3L10 21C10 21.5523 9.5523 22 9 22L6 22C3.7909 22 2 20.2091 2 18L2 6C2 3.7909 3.7909 2 6 2Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pndcq9b5c {
  d: path("M13 9L16 12L13 15");
}

.zuv35owmt {
  d: path("M18 3C19.6569 3 21 4.34315 21 6M21 18C21 19.6569 19.6569 21 18 21M13 3H14M13 21H14M21 10.5V13.5");
}

</style>
