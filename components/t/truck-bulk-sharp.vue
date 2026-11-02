<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="y3zoshb4k"/><path class="o_s21ac7z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:truck-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.o_s21ac7z {
  d: path("M4.236 16.832a3 3 0 1 1 5.527 2.338a3 3 0 0 1-5.527-2.338m10 0a3 3 0 1 1 5.527 2.338a3 3 0 0 1-5.527-2.338m-7.943 1.875a.999.999 0 1 0 1.414-1.414a.999.999 0 1 0-1.414 1.414m10 0a.999.999 0 1 0 1.414-1.414a.999.999 0 1 0-1.414 1.414");
}

.y3zoshb4k {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 5a1 1 0 0 1 1-1h10a1 1 0 0 1 1 1v2h3c.265 0 .52.105.707.293l4 4A1 1 0 0 1 22 12v6a1 1 0 0 1-1 1h-1.171a3 3 0 0 1-5.658 0H9.829a3 3 0 0 1-5.658 0H3a1 1 0 0 1-1-1Zm12 7h5.586l-3-3H14Zm-7.709 6.705l.002.002l.002.002a1 1 0 0 0 1.41 0l.002-.002l.002-.002a1 1 0 0 0 0-1.41l-.002-.002l-.002-.002a1 1 0 0 0-1.41 0l-.002.002l-.002.002a1 1 0 0 0 0 1.41m11.414.004l.002-.002l.002-.002a1 1 0 0 0 0-1.41l-.002-.002l-.002-.002a1 1 0 0 0-1.41 0l-.002.002l-.002.002a1 1 0 0 0 1.414 1.414");
}

</style>
