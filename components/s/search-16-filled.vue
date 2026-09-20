<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="w8puptbco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:search-16-filled" /></template>
<style>
.w8puptbco {
  fill: currentColor;
  d: path("M10.823 11.883a5.5 5.5 0 1 1 1.06-1.06l2.897 2.897a.75.75 0 1 1-1.06 1.06zM11.5 7.5a4 4 0 1 0-8 0a4 4 0 0 0 8 0");
}

</style>
