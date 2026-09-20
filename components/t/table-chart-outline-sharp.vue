<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v04t78brx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:table-chart-outline-sharp" /></template>
<style>
.v04t78brx {
  fill: currentColor;
  d: path("M4 20V4h16v16zM5 8.5h14V5H5zM5 19h2.885V9.5H5zm11.116 0H19V9.5h-2.884zm-7.231 0h6.23V9.5h-6.23z");
}

</style>
