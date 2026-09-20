<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vnd412bfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-insert-row-16-regular" /></template>
<style>
.vnd412bfh {
  fill: currentColor;
  d: path("M2.5 13a.5.5 0 0 0 0 1h11a.5.5 0 0 0 0-1zm0-11a.5.5 0 0 0 0 1h11a.5.5 0 0 0 0-1zM2 9.5A1.5 1.5 0 0 0 3.5 11h9A1.5 1.5 0 0 0 14 9.5v-3A1.5 1.5 0 0 0 12.5 5h-9A1.5 1.5 0 0 0 2 6.5zm1.5.5a.5.5 0 0 1-.5-.5v-3a.5.5 0 0 1 .5-.5H5v4zM6 10V6h4v4zm5 0V6h1.5a.5.5 0 0 1 .5.5v3a.5.5 0 0 1-.5.5z");
}

</style>
