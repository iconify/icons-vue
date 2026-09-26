<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bwnpao7ft"/><path class="r0knw1b4v"/><path class="btfg0oi0n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-percent-duotone" /></template>
<style>
.btfg0oi0n {
  d: path("M8 16L16 8");
}

.bwnpao7ft {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 6C2 3.7909 3.7909 2 6 2L18 2C20.2091 2 22 3.7909 22 6L22 18C22 20.2091 20.2091 22 18 22L6 22C3.7909 22 2 20.2091 2 18L2 6Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r0knw1b4v {
  fill: currentColor;
  d: path("M8.5 7C9.3285 7 10 7.6716 10 8.5C10 9.3285 9.3285 10 8.5 10C7.6716 10 7 9.3285 7 8.5C7 7.6716 7.6716 7 8.5 7ZM15.5 14C16.3285 14 17 14.6716 17 15.5C17 16.3285 16.3285 17 15.5 17C14.6716 17 14 16.3285 14 15.5C14 14.6716 14.6716 14 15.5 14Z");
  stroke: none;
}

</style>
