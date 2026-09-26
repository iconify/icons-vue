<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wqx_i9b-e"/><path class="q5usmxbcb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:smartphone-duotone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q5usmxbcb {
  d: path("M10.5 6L13.5 6");
}

.wqx_i9b-e {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20 6V18C20 20.7614 17.7614 23 15 23H9C6.23858 23 4 20.7614 4 18V6C4 3.23858 6.23858 1 9 1H15C17.7614 1 20 3.23858 20 6Z");
  stroke: none;
}

</style>
