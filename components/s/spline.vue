<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vbgkg67uo"/><path clip-rule="evenodd" class="j339ybc_n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:spline" /></template>
<style>
.j339ybc_n {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.5 17C17.5 17.8285 16.8285 18.5 16 18.5C15.1715 18.5 14.5 17.8285 14.5 17C14.5 16.1715 15.1715 15.5 16 15.5C16.8285 15.5 17.5 16.1715 17.5 17ZM9.5 7C9.5 7.8285 8.8285 8.5 8 8.5C7.1715 8.5 6.5 7.8285 6.5 7C6.5 6.1715 7.1715 5.5 8 5.5C8.8285 5.5 9.5 6.1715 9.5 7Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vbgkg67uo {
  d: path("M3 14L5 14C5.5523 14 6 14.4477 6 15L6 17C6 17.5523 5.5523 18 5 18L3 18C2.4477 18 2 17.5523 2 17L2 15C2 14.4477 2.4477 14 3 14ZM19 6L21 6C21.5523 6 22 6.4477 22 7L22 9C22 9.5523 21.5523 10 21 10L19 10C18.4477 10 18 9.5523 18 9L18 7C18 6.4477 18.4477 6 19 6ZM6 16C15 16 9 8 18 8");
}

</style>
