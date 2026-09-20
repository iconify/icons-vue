<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="whk5j8b_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-expand-28-regular" /></template>
<style>
.whk5j8b_o {
  fill: currentColor;
  d: path("M25.25 22a.75.75 0 0 1 0 1.5H7.75a.75.75 0 0 1 0-1.5zM8.5 7a6.5 6.5 0 1 1 0 13a6.5 6.5 0 0 1 0-13m0 2a.5.5 0 0 0-.5.5V13H4.5a.5.5 0 0 0 0 1H8v3.5a.5.5 0 0 0 1 0V14h3.5a.5.5 0 0 0 0-1H9V9.5a.5.5 0 0 0-.5-.5m16.75 6.5a.75.75 0 0 1 0 1.5h-7.5a.75.75 0 0 1 0-1.5zm0-6.5a.75.75 0 0 1 0 1.5h-7.5a.75.75 0 0 1 0-1.5zm0-6a.75.75 0 0 1 0 1.5H7.75a.75.75 0 0 1 0-1.5z");
}

</style>
