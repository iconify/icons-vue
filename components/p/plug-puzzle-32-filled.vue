<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rgw7u6rea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:plug-puzzle-32-filled" /></template>
<style>
.rgw7u6rea {
  fill: currentColor;
  d: path("M4 20.885c0-.765.62-1.385 1.385-1.385H6a3 3 0 0 0 0-6h-.615C4.62 13.5 4 12.88 4 12.115V9a5 5 0 0 1 5-5h3a1 1 0 1 1 0 2H9a3 3 0 0 0-3 3v2.5a5 5 0 0 1 0 10V24a3 3 0 0 0 3 3h11a3 3 0 0 0 3-3v-6a5 5 0 0 1-5-5V9.6c0-1.23.854-2.257 2-2.528V4a1 1 0 0 1 2 0v3h4V4a1 1 0 0 1 2 0v3.072A2.6 2.6 0 0 1 30 9.6V13a5 5 0 0 1-5 5v6a5 5 0 0 1-5 5H9a5 5 0 0 1-5-5z");
}

</style>
