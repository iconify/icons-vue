<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f9539ibzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:search-32-regular" /></template>
<style>
.f9539ibzy {
  fill: currentColor;
  d: path("M21.894 23.308A11.45 11.45 0 0 1 14.5 26C8.149 26 3 20.851 3 14.5S8.149 3 14.5 3S26 8.149 26 14.5a11.45 11.45 0 0 1-2.692 7.394l6.4 6.399a1 1 0 0 1-1.415 1.414zM24 14.5a9.5 9.5 0 1 0-19 0a9.5 9.5 0 0 0 19 0");
}

</style>
