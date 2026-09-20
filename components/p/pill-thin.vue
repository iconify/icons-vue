<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ex3cxe1vb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:pill-thin" /></template>
<style>
.ex3cxe1vb {
  fill: currentColor;
  d: path("M186.84 85.17a4 4 0 0 1 0 5.66l-24 24a4 4 0 1 1-5.66-5.66l24-24a4 4 0 0 1 5.66 0m26.75 26.91L112.08 213.57a49.26 49.26 0 0 1-69.67-69.65L143.92 42.43a49.26 49.26 0 0 1 69.67 69.65M154.35 160L96 101.66l-47.94 47.91a41.26 41.26 0 0 0 58.36 58.35Zm53.59-111.92a41.28 41.28 0 0 0-58.36 0L101.65 96L160 154.34l47.93-47.91a41.32 41.32 0 0 0 .01-58.35");
}

</style>
