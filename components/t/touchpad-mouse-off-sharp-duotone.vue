<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="x4bakrbzx"/><path class="v6m0zbn4m"/><path class="ahhqo1b4s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:touchpad-mouse-off-sharp-duotone" /></template>
<style>
.ahhqo1b4s {
  d: path("M1.7071 1.7071L22.2929 22.2929");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.v6m0zbn4m {
  stroke-opacity: 0.4;
  d: path("M11 16L2 16L2 2.4142M6.6569 2L20 2L20 7");
}

.x4bakrbzx {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21.5355 21.5355C20.6318 22.4392 19.3804 23 18 23C15.2386 23 13 20.7614 13 18L13 14C13 13.687 13.0288 13.3808 13.0838 13.0838ZM14.2971 10.6402C15.2118 9.6326 16.532 9 18 9C20.7614 9 23 11.2386 23 14L23 18C23 18.413 22.9498 18.8144 22.8553 19.1984Z");
  stroke: none;
}

</style>
