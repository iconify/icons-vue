<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="rnjfrmbsq"/><path class="rzz27iuhk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tag-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.rnjfrmbsq {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8 3h2c1.317 0 2.748.335 3.707 1.293l4 4a5.243 5.243 0 0 1 0 7.414l-2 2a5.243 5.243 0 0 1-7.414 0l-4-4C3.335 12.748 3 11.317 3 10V8a5 5 0 0 1 5-5");
}

.rzz27iuhk {
  d: path("M7.158 8.221a2 2 0 1 1 3.684 1.558a2 2 0 0 1-3.684-1.558");
}

</style>
