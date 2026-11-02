<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="k6epo0b3t"/><path class="w5l7jjf3a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tv-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.k6epo0b3t {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 10a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Z");
}

.w5l7jjf3a {
  d: path("M8.707 3.293L12 6.586l3.293-3.293a.999.999 0 1 1 1.414 1.414l-4 4a1 1 0 0 1-1.414 0l-4-4a.999.999 0 1 1 1.414-1.414");
}

</style>
