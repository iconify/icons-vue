<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ygqlu6xwg"/><path class="vsw7y8i0v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:passport-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.vsw7y8i0v {
  d: path("M8 10a4 4 0 1 1 8 0a4 4 0 0 1-8 0m2 0a2 2 0 1 0 3.999.001A2 2 0 0 0 10 10m5 6a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2Z");
}

.ygqlu6xwg {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 5a3 3 0 0 1 3-3h10a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3H7a3 3 0 0 1-3-3Z");
}

</style>
