<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jsxicibnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-navigate-next" /></template>
<style>
.jsxicibnj {
  fill: currentColor;
  d: path("M10.02 6L8.61 7.41L13.19 12l-4.58 4.59L10.02 18l6-6z");
}

</style>
