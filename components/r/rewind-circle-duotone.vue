<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="fxwgbbbhw"/><path class="w_fb6ebfm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:rewind-circle-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.fxwgbbbhw {
  d: path("M128 32a96 96 0 1 0 96 96a96 96 0 0 0-96-96m-16 132l-48-36l48-36Zm64 0l-48-36l48-36Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.w_fb6ebfm {
  d: path("M128 24a104 104 0 1 0 104 104A104.11 104.11 0 0 0 128 24m0 192a88 88 0 1 1 88-88a88.1 88.1 0 0 1-88 88M115.58 84.84a8 8 0 0 0-8.38.76l-48 36a8 8 0 0 0 0 12.8l48 36a8 8 0 0 0 4.8 1.6a8 8 0 0 0 8-8V92a8 8 0 0 0-4.42-7.16M104 148l-26.67-20L104 108Zm75.58-63.16a8 8 0 0 0-8.38.76l-48 36a8 8 0 0 0 0 12.8l48 36a8 8 0 0 0 4.8 1.6a8 8 0 0 0 8-8V92a8 8 0 0 0-4.42-7.16M168 148l-26.67-20L168 108Z");
}

</style>
