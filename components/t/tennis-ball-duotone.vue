<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="e4-4a4b-q"/><path class="wtpgy_gje"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:tennis-ball-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.e4-4a4b-q {
  d: path("M60.12 60.09A95.74 95.74 0 0 1 127.83 32A95.94 95.94 0 0 1 32 127.75a95.64 95.64 0 0 1 28.12-67.66M32 127.92v-.17Zm124.28 28.26a95.54 95.54 0 0 0-28.11 67.65A96 96 0 0 0 224 128.08a95.8 95.8 0 0 0-67.72 28.1M128.17 224v-.17Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wtpgy_gje {
  d: path("M201.57 54.46a104 104 0 1 0 0 147.08a103.4 103.4 0 0 0 0-147.08M65.75 65.77a87.63 87.63 0 0 1 53.66-25.31A87.3 87.3 0 0 1 94 94.06a87.42 87.42 0 0 1-53.62 25.35a87.58 87.58 0 0 1 25.37-53.64m-25.42 69.71a103.3 103.3 0 0 0 65-30.11a103.24 103.24 0 0 0 30.13-65a87.78 87.78 0 0 1 80.18 80.14a104 104 0 0 0-95.16 95.1a87.78 87.78 0 0 1-80.18-80.14Zm149.92 54.75a87.7 87.7 0 0 1-53.66 25.31a88 88 0 0 1 79-78.95a87.58 87.58 0 0 1-25.34 53.64");
}

</style>
