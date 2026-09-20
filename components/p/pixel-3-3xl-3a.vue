<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x7nnnbc_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:pixel-3-3xl-3a" /></template>
<style>
.x7nnnbc_j {
  fill: currentColor;
  d: path("M9 6q.425 0 .713-.288T10 5q0-.425-.288-.713T9 4q-.425 0-.713.288T8 5q0 .425.288.713T9 6ZM7 23q-.825 0-1.413-.588T5 21V3q0-.825.588-1.413T7 1h10q.825 0 1.413.588T19 3v18q0 .825-.588 1.413T17 23H7Z");
}

</style>
