<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="h98u47b-d"/><path class="vvcqz7bor"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:tumbler-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.h98u47b-d {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20.7398 12.1375L19.4905 21.1375C19.4219 21.6319 18.9992 22 18.5 22L5.5 22C5.0008 22 4.5781 21.6319 4.5095 21.1375L2.0109 3.1375C2.0046 3.0919 2.0014 3.046 2.0014 3C2.0014 2.4477 2.4491 2 3.0014 2L20.9986 2C21.5509 2 21.9986 2.4477 21.9986 3C21.9986 3.046 21.9954 3.0919 21.9891 3.1375Z");
  stroke: none;
}

.vvcqz7bor {
  d: path("M3.6367 7.567C4.9787 7.1908 6.3662 7 7.7604 7C9.1948 7 10.622 7.202 12 7.6C13.378 7.998 14.8052 8.2 16.2396 8.2C17.631 8.2 19.0156 8.0099 20.355 7.6353M3.0014 3L20.9986 3L18.5 21L5.5 21ZM9.8145 13.1807L13.4193 12.4145L14.1855 16.0193L10.5807 16.7855Z");
}

</style>
