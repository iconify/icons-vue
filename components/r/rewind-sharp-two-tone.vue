<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="z82wjixvo"/><path class="rxcsbu8ge"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:rewind-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rxcsbu8ge {
  d: path("M22 17.998L13.5417 12L22 6.002L22 17.998ZM10 17.998L2 12L10 6.002L10 17.998Z");
}

.z82wjixvo {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21.4216 18.8137L12.9633 12.8157C12.4012 12.4171 12.4012 11.5829 12.9633 11.1843L21.4216 5.1863C22.0838 4.7167 23 5.1902 23 6.002L23 17.998C23 18.8098 22.0838 19.2833 21.4216 18.8137ZM9.4001 18.7981L1.4001 12.8001C0.8666 12.4001 0.8666 11.5999 1.4001 11.1999L9.4001 5.2019C10.0594 4.7076 11 5.178 11 6.002L11 17.998C11 18.822 10.0594 19.2924 9.4001 18.7981Z");
  stroke: none;
}

</style>
