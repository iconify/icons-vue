<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="zoe_37m-q"/><path class="lc06zu-1s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:windmill-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.lc06zu-1s {
  d: path("M1 22H6M6 22H18M6 22L7 18M18 22H23M18 22L17 18M7 18L8.071 13.72M7 18H17M17 18L15.929 13.72M12 5.22L15.445 2L18.217 4.54L14.756 8L18.202 11.45L15.445 14.2L12 10.76L8.554 14.2L5.798 11.45L9.244 8L5.798 4.55L8.554 2L12 5.22Z");
}

.zoe_37m-q {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M14.762 1.27C15.143 0.91 15.736 0.91 16.121 1.26L18.893 3.8C19.094 3.99 19.211 4.24 19.217 4.52C19.223 4.79 19.117 5.05 18.924 5.25L16.17 8L18.908 10.74C19.096 10.93 19.201 11.18 19.201 11.45C19.201 11.71 19.096 11.96 18.908 12.15L17.036 14.02L18.78 21H23V23H1V21H5.22L6.963 14.03L5.091 12.15C4.701 11.76 4.701 11.13 5.091 10.74L7.829 8L5.091 5.26C4.899 5.07 4.793 4.81 4.798 4.54C4.803 4.26 4.919 4.01 5.118 3.82L7.874 1.27C8.259 0.91 8.854 0.91 9.237 1.27L11.999 3.85L14.762 1.27Z");
  stroke: none;
}

</style>
