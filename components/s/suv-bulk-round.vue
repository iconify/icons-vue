<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="y7j30js-o"/><path class="o_s21ac7z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:suv-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.o_s21ac7z {
  d: path("M4.236 16.832a3 3 0 1 1 5.527 2.338a3 3 0 0 1-5.527-2.338m10 0a3 3 0 1 1 5.527 2.338a3 3 0 0 1-5.527-2.338m-7.943 1.875a.999.999 0 1 0 1.414-1.414a.999.999 0 1 0-1.414 1.414m10 0a.999.999 0 1 0 1.414-1.414a.999.999 0 1 0-1.414 1.414");
}

.y7j30js-o {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9.829 19a3 3 0 0 1-5.7-.128A3.005 3.005 0 0 1 2 16v-6a5 5 0 0 1 5-5h6c.265 0 .52.105.707.293L17.414 9H19a3 3 0 0 1 3 3v4c0 1.32-.866 2.487-2.128 2.872a3 3 0 0 1-5.701.128ZM7 7a3 3 0 0 0-3 3v1h5V7Zm5.586 0H11v4h5.586ZM6.291 18.705l.002.002l.002.002a1 1 0 0 0 1.41 0l.002-.002l.002-.002a1 1 0 0 0 0-1.41l-.002-.002l-.002-.002a1 1 0 0 0-1.41 0l-.002.002l-.002.002a1 1 0 0 0 0 1.41m11.414.004l.002-.002l.002-.002a1 1 0 0 0 0-1.41l-.002-.002l-.002-.002a1 1 0 0 0-1.41 0l-.002.002l-.002.002a1 1 0 0 0 1.414 1.414");
}

</style>
