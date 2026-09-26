<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="nmpa5bb2m"/><path class="l0nljwb2n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:moon-star-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.l0nljwb2n {
  d: path("M18.9689 1.4226L18.9689 9.5774M15.4378 3.4613L22.5 7.5387M22.5 3.4613L15.4378 7.5387");
}

.nmpa5bb2m {
  fill: currentColor;
  d: path("M21 13C21 18.3848 16.3848 23 11 23C5.6152 23 1 18.3848 1 13C1 7.6152 5.6152 3 11 3C11.8385 3 12.3047 3.9699 11.7809 4.6247C9.9814 6.874 10.1425 9.7837 12.1794 11.8206C14.2163 13.8575 17.126 14.0186 19.3753 12.2191C20.0301 11.6953 21 12.1615 21 13Z");
  stroke: none;
}

</style>
