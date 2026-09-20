<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m7qlxg70a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-simple-48-filled" /></template>
<style>
.m7qlxg70a {
  fill: currentColor;
  d: path("M6 10.75A4.75 4.75 0 0 1 10.75 6h12v16.75H6zm0 14.5v12A4.75 4.75 0 0 0 10.75 42h12V25.25zM25.25 42h12A4.75 4.75 0 0 0 42 37.25v-12H25.25zM42 22.75v-12A4.75 4.75 0 0 0 37.25 6h-12v16.75z");
}

</style>
