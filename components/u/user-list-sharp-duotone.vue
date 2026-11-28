<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="e6n5cdcwd"/><path class="b4yx8jbjb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:user-list-sharp-duotone" /></template>
<style>
.b4yx8jbjb {
  d: path("M14 13L15 13L21 13L22 13M14 17L15 17L22 17L23 17M14 21L15 21L19 21L20 21");
}

.e6n5cdcwd {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 22H2C1.44772 22 1 21.5523 1 21V19C1 15.134 4.13402 12 8 12H12V22ZM9 2C11.2092 2 13 3.79082 13 6C13 8.20918 11.2092 10 9 10C6.79094 10 5 8.20921 5 6C5 3.79079 6.79094 2 9 2Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
