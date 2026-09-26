<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="o30i8gi7t"/><path class="orm3uibci"/><path class="j3akw_70p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:train-duotone" /></template>
<style>
.j3akw_70p {
  fill: currentColor;
  d: path("M10 13.5C10 14.3284 9.3284 15 8.5 15C7.6716 15 7 14.3284 7 13.5C7 12.6716 7.6716 12 8.5 12C9.3284 12 10 12.6716 10 13.5ZM17 13.5C17 14.3284 16.3284 15 15.5 15C14.6716 15 14 14.3284 14 13.5C14 12.6716 14.6716 12 15.5 12C16.3284 12 17 12.6716 17 13.5Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o30i8gi7t {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7 1L17 1C19.2091 1 21 2.7909 21 5L21 15C21 17.2091 19.2091 19 17 19L7 19C4.7909 19 3 17.2091 3 15L3 5C3 2.7909 4.7909 1 7 1Z");
  stroke: none;
}

.orm3uibci {
  d: path("M4 9L20 9M4 5L2 5M20 5L22 5M7 18L5 22M17 18L19 22");
}

</style>
