<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="c0ev15b6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:panel-left-header-16-regular" /></template>
<style>
.c0ev15b6h {
  fill: currentColor;
  d: path("M4.5 3A2.5 2.5 0 0 0 2 5.5v5A2.5 2.5 0 0 0 4.5 13h7a2.5 2.5 0 0 0 2.5-2.5v-5A2.5 2.5 0 0 0 11.5 3zM13 6.5H7V4h4.5A1.5 1.5 0 0 1 13 5.5zM6 4v8H4.5A1.5 1.5 0 0 1 3 10.5v-5A1.5 1.5 0 0 1 4.5 4zm1 3.5h6v3a1.5 1.5 0 0 1-1.5 1.5H7z");
}

</style>
