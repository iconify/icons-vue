<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="sjtat7zsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-expand-32-light" /></template>
<style>
.sjtat7zsq {
  fill: currentColor;
  d: path("M29.5 26a.5.5 0 0 1 0 1h-22a.5.5 0 0 1 0-1zM8.75 9a6.75 6.75 0 1 1 0 13.5a6.75 6.75 0 0 1 0-13.5m0 3a.75.75 0 0 0-.75.75V15H5.75a.75.75 0 0 0 0 1.5H8v2.25a.75.75 0 0 0 1.5 0V16.5h2.25a.75.75 0 0 0 0-1.5H9.5v-2.25a.75.75 0 0 0-.75-.75m20.75 7a.5.5 0 0 1 0 1h-11a.5.5 0 0 1 0-1zm0-8a.5.5 0 0 1 0 1h-11a.5.5 0 0 1 0-1zm0-7a.5.5 0 0 1 0 1h-22a.5.5 0 0 1 0-1z");
}

</style>
