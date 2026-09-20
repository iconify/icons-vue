<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="ky83vw3xc"/><path class="wx9f2dbyh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:usb-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ky83vw3xc {
  d: path("M160 64a24 24 0 1 1-24-24a24 24 0 0 1 24 24m40 32v64l48-32Zm-48 72h-32a8 8 0 0 0-8 8v32a8 8 0 0 0 8 8h32a8 8 0 0 0 8-8v-32a8 8 0 0 0-8-8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wx9f2dbyh {
  d: path("m252.44 121.34l-48-32A8 8 0 0 0 192 96v24H72V72h33a32 32 0 1 0 0-16H72a16 16 0 0 0-16 16v48H8a8 8 0 0 0 0 16h48v48a16 16 0 0 0 16 16h32v8a16 16 0 0 0 16 16h32a16 16 0 0 0 16-16v-32a16 16 0 0 0-16-16h-32a16 16 0 0 0-16 16v8H72v-48h120v24a8 8 0 0 0 12.44 6.66l48-32a8 8 0 0 0 0-13.32M136 48a16 16 0 1 1-16 16a16 16 0 0 1 16-16m-16 128h32v32h-32Zm88-30.95V111l25.58 17Z");
}

</style>
