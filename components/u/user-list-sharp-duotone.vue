<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="t7091ltxz"/><path class="b4yx8jbjb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:user-list-sharp-duotone" /></template>
<style>
.b4yx8jbjb {
  d: path("M14 13L15 13L21 13L22 13M14 17L15 17L22 17L23 17M14 21L15 21L19 21L20 21");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.t7091ltxz {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10 13C10.3396 13 10.6733 13.0255 11 13.0723V22H2C1.44772 22 1 21.5523 1 21V20C1 16.134 4.13402 13 8 13H10ZM9 3C11.2092 3 13 4.79082 13 7C13 9.20918 11.2092 11 9 11C6.79094 11 5 9.20921 5 7C5 4.79079 6.79094 3 9 3Z");
  stroke: none;
}

</style>
