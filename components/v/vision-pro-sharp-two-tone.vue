<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="oq3mrnbul"/><path class="nk9w0hbdg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:vision-pro-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nk9w0hbdg {
  d: path("M7 7L17 7C19.7614 7 22 9.2386 22 12C22 14.7614 19.7614 17 17 17L15.39 17L13.61 14.3166L10.39 14.3166L8.61 17L7 17C4.2386 17 2 14.7614 2 12C2 9.2386 4.2386 7 7 7Z");
}

.oq3mrnbul {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7 6L17 6C20.3137 6 23 8.6863 23 12C23 15.3137 20.3137 18 17 18L15.39 18C15.0548 18 14.7419 17.8321 14.5566 17.5528L13.0734 15.3166L10.9266 15.3166L9.4434 17.5528C9.2581 17.8321 8.9452 18 8.61 18L7 18C3.6863 18 1 15.3137 1 12C1 8.6863 3.6863 6 7 6Z");
  stroke: none;
}

</style>
