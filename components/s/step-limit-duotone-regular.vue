<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="i286cabna"/><path class="m93rqjk1p"/><path class="v8t37dedd"/><path class="gg6jr8oaf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:step-limit-duotone-regular" /></template>
<style>
.gg6jr8oaf {
  d: path("M21 4v16");
}

.i286cabna {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 6h5v5h5v5h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.m93rqjk1p {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M21 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.v8t37dedd {
  d: path("M3 6h5v5h5v5h5");
}

</style>
