<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="noapnj96o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:toggle-right-16-regular" /></template>
<style>
.noapnj96o {
  fill: currentColor;
  d: path("M11 10a2 2 0 1 0 0-4a2 2 0 0 0 0 4M1 8a4 4 0 0 1 4-4h6a4 4 0 0 1 0 8H5a4 4 0 0 1-4-4m4-3a3 3 0 0 0 0 6h6a3 3 0 1 0 0-6z");
}

</style>
