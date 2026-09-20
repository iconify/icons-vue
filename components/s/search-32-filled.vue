<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xwv5pzh_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:search-32-filled" /></template>
<style>
.xwv5pzh_o {
  fill: currentColor;
  d: path("M21.7 23.467A11.45 11.45 0 0 1 14.5 26C8.149 26 3 20.851 3 14.5S8.149 3 14.5 3S26 8.149 26 14.5c0 2.725-.948 5.229-2.532 7.2l6.167 6.166a1.25 1.25 0 0 1-1.768 1.768zm1.8-8.967a9 9 0 1 0-18 0a9 9 0 0 0 18 0");
}

</style>
