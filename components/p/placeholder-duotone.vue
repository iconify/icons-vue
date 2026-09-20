<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="rl1dq4bco"/><path class="mlfntsbbz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:placeholder-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.mlfntsbbz {
  d: path("M224 48a16 16 0 0 0-16-16H48a15.9 15.9 0 0 0-10.66 4.1a9 9 0 0 0-1.24 1.24A15.9 15.9 0 0 0 32 48v160a16 16 0 0 0 16 16h160a15.9 15.9 0 0 0 10.66-4.1a7 7 0 0 0 .65-.59a6 6 0 0 0 .58-.65A15.87 15.87 0 0 0 224 208Zm-16 148.7L59.31 48H208ZM48 59.31L196.69 208H48Z");
}

.rl1dq4bco {
  d: path("M216 48v160a8 8 0 0 1-8 8H48a8 8 0 0 1-8-8V48a8 8 0 0 1 8-8h160a8 8 0 0 1 8 8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
