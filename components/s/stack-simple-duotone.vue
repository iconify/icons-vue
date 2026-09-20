<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="o__-ilb4s"/><path class="skmgcwhgy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:stack-simple-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.o__-ilb4s {
  d: path("m240 104l-112 64l-112-64l112-64Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.skmgcwhgy {
  d: path("m12 111l112 64a8 8 0 0 0 7.94 0l112-64a8 8 0 0 0 0-13.9l-112-64a8 8 0 0 0-7.94 0l-112 64a8 8 0 0 0 0 13.9m116-61.79L223.87 104L128 158.79L32.13 104ZM247 140a8 8 0 0 1-3 11l-112 64a8 8 0 0 1-7.94 0L12 151a8 8 0 1 1 8-13.95l108 61.74l108-61.74a8 8 0 0 1 11 2.95");
}

</style>
