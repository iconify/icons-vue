<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="e55j300_i"/><path class="n3tw5u9xl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:unite-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.e55j300_i {
  d: path("M232 160a72 72 0 0 1-143.6 7.6a72 72 0 1 1 79.2-79.2A72 72 0 0 1 232 160");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.n3tw5u9xl {
  d: path("M174.63 81.37a80 80 0 1 0-93.26 93.26a80 80 0 1 0 93.26-93.26M32 96a64 64 0 0 1 126-16a80.08 80.08 0 0 0-77.95 78A64.11 64.11 0 0 1 32 96m128 0a64.07 64.07 0 0 1-64 64a64.07 64.07 0 0 1 64-64m0 128a64.11 64.11 0 0 1-62-48a80.08 80.08 0 0 0 78-78a64 64 0 0 1-16 126");
}

</style>
