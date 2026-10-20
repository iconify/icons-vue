<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="n5sdg2b4j"/><path class="g7e-0ub7t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:mouse-pointer-sharp-two-tone" /></template>
<style>
.g7e-0ub7t {
  d: path("M3 3L21 9.2011L15.008 12.1796L21 18.5858L18.5858 21L12.2249 15.0533L8.9427 21Z");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.n5sdg2b4j {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3.3257 2.0545L21.3257 8.2556C21.7292 8.3946 22 8.7743 22 9.2011C22 9.5807 21.7851 9.9276 21.4451 10.0966L16.6557 12.4773L21.7303 17.9027C21.9036 18.088 22 18.3321 22 18.5858C22 18.851 21.8946 19.1054 21.7071 19.2929L19.2929 21.7071C19.1054 21.8946 18.851 22 18.5858 22C18.3322 22 18.0881 21.9037 17.9029 21.7305L12.48 16.6607L9.8182 21.4832C9.6422 21.802 9.3069 22 8.9427 22C8.5112 22 8.1284 21.7232 7.9931 21.3135L2.0504 3.3135C2.017 3.2124 2 3.1065 2 3C2 2.4477 2.4477 2 3 2C3.1108 2 3.2209 2.0184 3.3257 2.0545Z");
  stroke: none;
}

</style>
