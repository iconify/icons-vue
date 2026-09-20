<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="qce-44lin"/><path class="y3dkg3beb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:shuffle-simple-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.qce-44lin {
  d: path("m48 48l80 80l-80 80Zm80 80l80 80V48Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.y3dkg3beb {
  d: path("M216 48v40a8 8 0 0 1-16 0V67.31L156.28 111A8 8 0 0 1 145 99.72L188.69 56H168a8 8 0 0 1 0-16h40a8 8 0 0 1 8 8m-8 112a8 8 0 0 0-8 8v20.69L53.66 42.34a8 8 0 0 0-11.32 11.32L188.69 200H168a8 8 0 0 0 0 16h40a8 8 0 0 0 8-8v-40a8 8 0 0 0-8-8M99.72 145l-57.38 57.34a8 8 0 0 0 11.32 11.32L111 156.28A8 8 0 0 0 99.72 145");
}

</style>
