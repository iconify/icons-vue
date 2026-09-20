<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="uxxq3qbbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:record-12-regular" /></template>
<style>
.uxxq3qbbv {
  fill: currentColor;
  d: path("M6 9a3 3 0 1 0 0-6a3 3 0 0 0 0 6m5-3A5 5 0 1 1 1 6a5 5 0 0 1 10 0m-1 0a4 4 0 1 0-8 0a4 4 0 0 0 8 0");
}

</style>
