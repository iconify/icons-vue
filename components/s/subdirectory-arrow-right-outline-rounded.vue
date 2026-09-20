<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kmazxrbrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:subdirectory-arrow-right-outline-rounded" /></template>
<style>
.kmazxrbrg {
  fill: currentColor;
  d: path("M13 19.575q0-.4.3-.7L16.175 16H7q-.825 0-1.412-.587T5 14V5q0-.425.288-.712T6 4t.713.288T7 5v9h9.175l-2.9-2.9q-.3-.3-.288-.7t.288-.7q.3-.3.7-.312t.7.287L19.3 14.3q.15.15.212.325t.063.375t-.063.375t-.212.325l-4.575 4.575q-.3.3-.712.3t-.713-.3t-.3-.7");
}

</style>
