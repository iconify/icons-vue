<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="uv88-nbel"/><path class="n8s1dabzs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:touchpad-mouse-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.n8s1dabzs {
  d: path("M11 16L2 16L2 2L20 2L20 7M18 10C20.2091 10 22 11.7909 22 14L22 18C22 20.2091 20.2091 22 18 22C15.7909 22 14 20.2091 14 18L14 14C14 11.7909 15.7909 10 18 10ZM18 13L18 16");
}

.uv88-nbel {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21.5355 21.5355C20.6318 22.4392 19.3804 23 18 23C15.2386 23 13 20.7614 13 18L13 14C13 11.2386 15.2386 9 18 9C20.7614 9 23 11.2386 23 14L23 18C23 19.3804 22.4392 20.6318 21.5355 21.5355Z");
  stroke: none;
}

</style>
