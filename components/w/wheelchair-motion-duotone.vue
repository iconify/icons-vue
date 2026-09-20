<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="vdrgqrbav"/><path class="yvom2gbag"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:wheelchair-motion-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.vdrgqrbav {
  d: path("M200 48a24 24 0 1 1-24-24a24 24 0 0 1 24 24");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yvom2gbag {
  d: path("M176 80a32 32 0 1 0-32-32a32 32 0 0 0 32 32m0-48a16 16 0 1 1-16 16a16 16 0 0 1 16-16m-8 136a64 64 0 1 1-64-64a8 8 0 0 1 0 16a48 48 0 1 0 48 48a8 8 0 0 1 16 0m38.19-37.07a8 8 0 0 1 1.65 6.64l-16 80A8 8 0 0 1 184 224a7.8 7.8 0 0 1-1.58-.16a8 8 0 0 1-6.27-9.41L190.24 144H128a8 8 0 0 1-6.94-12l20.06-34.9a80.09 80.09 0 0 0-88 9.17A8 8 0 1 1 42.91 94a96 96 0 0 1 113.46-6.42a8 8 0 0 1 2.57 10.69L141.82 128H200a8 8 0 0 1 6.19 2.93");
}

</style>
