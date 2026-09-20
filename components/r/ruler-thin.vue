<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="g1377wz2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:ruler-thin" /></template>
<style>
.g1377wz2b {
  fill: currentColor;
  d: path("M232.49 76.2L179.8 23.51a12 12 0 0 0-17 0L23.51 162.83a12 12 0 0 0 0 17l52.69 52.66a12 12 0 0 0 17 0L232.49 93.17a12 12 0 0 0 0-16.97m-5.66 11.31L87.51 226.83a4 4 0 0 1-5.65 0l-52.69-52.69a4 4 0 0 1 0-5.65L64 133.66l29.17 29.17a4 4 0 1 0 5.66-5.66L69.65 128L96 101.66l29.17 29.17a4 4 0 0 0 5.66-5.66L101.65 96L128 69.66l29.17 29.17a4 4 0 1 0 5.66-5.66L133.66 64l34.83-34.83a4 4 0 0 1 5.65 0l52.69 52.69a4 4 0 0 1 0 5.65");
}

</style>
