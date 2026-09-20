<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="vwaq_1b8y"/><path class="k21wg3vnj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:wifi-low-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.k21wg3vnj {
  d: path("M247.89 80.91a15.93 15.93 0 0 0-6.17-10.81A186.67 186.67 0 0 0 128 32A186.67 186.67 0 0 0 14.28 70.1a15.93 15.93 0 0 0-6.17 10.81a15.65 15.65 0 0 0 3.54 11.89l104 125.43A15.93 15.93 0 0 0 128 224a15.93 15.93 0 0 0 12.31-5.77l104-125.43a15.65 15.65 0 0 0 3.58-11.89M128 208l-32.1-38.7a60 60 0 0 1 64.2 0Zm42.37-51.08a75.89 75.89 0 0 0-84.74 0L24.09 82.74A170.76 170.76 0 0 1 128 48a170.76 170.76 0 0 1 103.91 34.74Z");
}

.vwaq_1b8y {
  d: path("m171.68 167.88l-37.53 45.24a8 8 0 0 1-12.3 0l-37.53-45.24a68 68 0 0 1 87.36 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
