<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="icps4mb-p"/><path class="jk-rmmbdp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:speaker-simple-low-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.icps4mb-p {
  d: path("M160 32v192l-72-56H40a8 8 0 0 1-8-8V96a8 8 0 0 1 8-8h48Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.jk-rmmbdp {
  d: path("M163.51 24.81a8 8 0 0 0-8.42.88L85.25 80H40a16 16 0 0 0-16 16v64a16 16 0 0 0 16 16h45.25l69.84 54.31A8 8 0 0 0 168 224V32a8 8 0 0 0-4.49-7.19M152 207.64l-59.09-45.95A7.94 7.94 0 0 0 88 160H40V96h48a7.94 7.94 0 0 0 4.91-1.69L152 48.36ZM208 104v48a8 8 0 0 1-16 0v-48a8 8 0 0 1 16 0");
}

</style>
