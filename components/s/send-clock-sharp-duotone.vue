<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="xczyuaciy"/><path class="tsntr_b0q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:send-clock-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tsntr_b0q {
  d: path("M22 15.5C22 19.0899 19.0899 22 15.5 22C11.9101 22 9 19.0899 9 15.5C9 11.9101 11.9101 9 15.5 9C19.0899 9 22 11.9101 22 15.5ZM15.5 12L15.5 15.5L19 15.5");
}

.xczyuaciy {
  stroke-opacity: 0.4;
  d: path("M6.5744 11.0404L6.1382 10.7426L2 7.9174L22 2L20.7043 6.3794L20.4923 7.0957M18.2562 5.7438L18.5491 5.4509L22 2");
}

</style>
