<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j4oe79bfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:toggle-right-48-regular" /></template>
<style>
.j4oe79bfp {
  fill: currentColor;
  d: path("M38.5 24a5 5 0 1 0-10 0a5 5 0 0 0 10 0m5.5 0c0-5.523-4.477-10-10-10H14C8.477 14 4 18.477 4 24s4.477 10 10 10h20c5.523 0 10-4.477 10-10m-10-7.5a7.5 7.5 0 0 1 0 15H14a7.5 7.5 0 0 1 0-15z");
}

</style>
