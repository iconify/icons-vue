<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="f698frfdr"/><path class="u7wmp9-vo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:touchpad-mouse-fill" /></template>
<style>
.f698frfdr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M21.5355 21.5355C20.6318 22.4392 19.3804 23 18 23C15.2386 23 13 20.7614 13 18L13 14C13 11.2386 15.2386 9 18 9C20.7614 9 23 11.2386 23 14L23 18C23 19.3804 22.4392 20.6318 21.5355 21.5355ZM19 14C19 13.4477 18.5523 13 18 13C17.4477 13 17 13.4477 17 14L17 15C17 15.5523 17.4477 16 18 16C18.5523 16 19 15.5523 19 15Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.u7wmp9-vo {
  d: path("M10 16H5C3.3431 16 2 14.6569 2 13V5C2 3.3431 3.3431 2 5 2H17C18.6569 2 20 3.3431 20 5V6");
}

</style>
