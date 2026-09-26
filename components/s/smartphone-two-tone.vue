<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wqx_i9b-e"/><path class="pwnwd6bwk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:smartphone-two-tone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pwnwd6bwk {
  d: path("M10.5 6H13.5M19 18V6C19 3.79086 17.2091 2 15 2H9C6.79086 2 5 3.79086 5 6V18C5 20.2091 6.79086 22 9 22H15C17.2091 22 19 20.2091 19 18Z");
}

.wqx_i9b-e {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20 6V18C20 20.7614 17.7614 23 15 23H9C6.23858 23 4 20.7614 4 18V6C4 3.23858 6.23858 1 9 1H15C17.7614 1 20 3.23858 20 6Z");
  stroke: none;
}

</style>
