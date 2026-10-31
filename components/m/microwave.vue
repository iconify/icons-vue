<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bdqdnobsr"/><path clip-rule="evenodd" class="nxtzw_78l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:microwave" /></template>
<style>
.bdqdnobsr {
  d: path("M5 3L19 3C20.6569 3 22 4.3431 22 6L22 16C22 17.6569 20.6569 19 19 19L5 19C3.3431 19 2 17.6569 2 16L2 6C2 4.3431 3.3431 3 5 3ZM6 19L6 21M18 19L18 21M8 7L12 7C13.1046 7 14 7.8954 14 9L14 13C14 14.1046 13.1046 15 12 15L8 15C6.8954 15 6 14.1046 6 13L6 9C6 7.8954 6.8954 7 8 7Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nxtzw_78l {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19 9C19 9.5523 18.5523 10 18 10C17.4477 10 17 9.5523 17 9C17 8.4477 17.4477 8 18 8C18.5523 8 19 8.4477 19 9ZM19 13C19 13.5523 18.5523 14 18 14C17.4477 14 17 13.5523 17 13C17 12.4477 17.4477 12 18 12C18.5523 12 19 12.4477 19 13Z");
  stroke: none;
}

</style>
