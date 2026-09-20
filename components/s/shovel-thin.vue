<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="sdh31ccgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:shovel-thin" /></template>
<style>
.sdh31ccgb {
  fill: currentColor;
  d: path("m242.83 61.17l-48-48a4 4 0 0 0-5.66 5.66L210.34 40l-76.68 76.69l-37.17-37.18a12 12 0 0 0-17 0l-56 56A11.93 11.93 0 0 0 20 144v80a12 12 0 0 0 12 12h80a12 12 0 0 0 8.49-3.51l56-56a12 12 0 0 0 0-17l-37.18-37.17L216 45.66l21.17 21.17a4 4 0 1 0 5.66-5.66m-72 104a4 4 0 0 1 0 5.66l-56 56A4 4 0 0 1 112 228H32a4 4 0 0 1-4-4v-80a4 4 0 0 1 1.17-2.83l56-56a4 4 0 0 1 5.66 0L128 122.34l-42.83 42.83a4 4 0 0 0 5.66 5.66L133.66 128Z");
}

</style>
