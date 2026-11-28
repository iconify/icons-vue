<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="w6bmgccdj"/><path class="uurfrgb9z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-dashed-pen-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.uurfrgb9z {
  d: path("M3 7V3H7M21 17V21H17M14.5 21H9.5M7 21H3V17M3 14.5V9.5M9.5 3H13.283M21 10.717V14.5");
}

.w6bmgccdj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M10.871 14.428L14.996 12.779C15.122 12.728 15.236 12.653 15.332 12.557L21.195 6.694C22.171 5.718 22.171 3.782 21.195 2.805C20.218 1.829 18.282 1.829 17.305 2.805L11.443 8.668C11.347 8.764 11.272 8.878 11.221 9.004L9.572 13.129C9.245 13.945 10.055 14.755 10.871 14.428Z");
  stroke: none;
}

</style>
