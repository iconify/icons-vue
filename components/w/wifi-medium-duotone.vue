<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="f7maylbtg"/><path class="fistrqrmp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:wifi-medium-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.f7maylbtg {
  d: path("m202.33 130.94l-68.18 82.18a8 8 0 0 1-12.3 0l-68.18-82.18a116 116 0 0 1 148.66 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.fistrqrmp {
  d: path("M247.89 80.91a15.93 15.93 0 0 0-6.17-10.81A186.67 186.67 0 0 0 128 32A186.67 186.67 0 0 0 14.28 70.1a15.93 15.93 0 0 0-6.17 10.81a15.65 15.65 0 0 0 3.54 11.89l104 125.43A15.93 15.93 0 0 0 128 224a15.93 15.93 0 0 0 12.31-5.77l104-125.43a15.65 15.65 0 0 0 3.58-11.89M128 208l-62.87-75.8a107.89 107.89 0 0 1 125.74 0Zm73.12-88.16a124 124 0 0 0-146.24 0l-30.79-37.1A170.76 170.76 0 0 1 128 48a170.76 170.76 0 0 1 103.91 34.74Z");
}

</style>
