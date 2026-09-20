<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="zx-9cg3-m"/><path class="rlnzexbhg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:orange-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.rlnzexbhg {
  d: path("M165.87 72.58A64.06 64.06 0 0 0 200 16a8 8 0 0 0-8-8h-8a64 64 0 0 0-56 33.06A64 64 0 0 0 72 8h-8a8 8 0 0 0 0 16h8a48.08 48.08 0 0 1 47.4 40.42a88 88 0 1 0 46.47 8.16M183.33 24a48.09 48.09 0 0 1-46.66 40a48.09 48.09 0 0 1 46.66-40M128 224a72 72 0 1 1 72-72a72.08 72.08 0 0 1-72 72m55.89-62.68a57.5 57.5 0 0 1-46.57 46.57a8.5 8.5 0 0 1-1.32.11a8 8 0 0 1-1.31-15.89a41.29 41.29 0 0 0 33.43-33.43a8 8 0 0 1 15.78 2.64Z");
}

.zx-9cg3-m {
  d: path("M208 152a80 80 0 1 1-80-80a80 80 0 0 1 80 80");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
