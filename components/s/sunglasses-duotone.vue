<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="vmruz2bfs"/><path class="y_im9hail"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:sunglasses-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.vmruz2bfs {
  d: path("M32 136h72v28a36 36 0 0 1-72 0Zm120 0v28a36 36 0 0 0 72 0v-28Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.y_im9hail {
  d: path("M200 40a8 8 0 0 0 0 16a16 16 0 0 1 16 16v56H40V72a16 16 0 0 1 16-16a8 8 0 0 0 0-16a32 32 0 0 0-32 32v92a44 44 0 0 0 88 0v-20h32v20a44 44 0 0 0 88 0V72a32 32 0 0 0-32-32m12.63 137.31L179.31 144H216v20a27.8 27.8 0 0 1-3.37 13.31M40 164v-16.69l41.31 41.32A28 28 0 0 1 40 164m56 0a27.8 27.8 0 0 1-3.37 13.31L59.31 144H96Zm64 0v-16.69l41.31 41.32A28 28 0 0 1 160 164");
}

</style>
