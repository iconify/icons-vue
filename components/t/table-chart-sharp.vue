<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h2a8yba1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:table-chart-sharp" /></template>
<style>
.h2a8yba1e {
  fill: currentColor;
  d: path("M4 8.5V4h16v4.5zM4 20V9.5h3.885V20zm12.116 0V9.5H20V20zm-7.231 0V9.5h6.23V20z");
}

</style>
