<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="j9xjscxda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:swipe-right-20-regular" /></template>
<style>
.j9xjscxda {
  fill: currentColor;
  d: path("M6 6a4 4 0 0 1 3.71 2.5H8.598a3 3 0 1 0 0 3h1.11A4.001 4.001 0 0 1 2 10a4 4 0 0 1 4-4m8.854 7.354l3-3a.5.5 0 0 0 0-.708l-3-3a.5.5 0 1 0-.707.708L16.293 9.5H5.5a.5.5 0 0 0 0 1h10.793l-2.146 2.146a.5.5 0 0 0 .707.708");
}

</style>
