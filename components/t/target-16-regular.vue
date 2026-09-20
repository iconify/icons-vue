<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zfiqf8mrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:target-16-regular" /></template>
<style>
.zfiqf8mrc {
  fill: currentColor;
  d: path("M8 9a1 1 0 1 0 0-2a1 1 0 0 0 0 2M4.5 8a3.5 3.5 0 1 1 7 0a3.5 3.5 0 0 1-7 0M8 5.5a2.5 2.5 0 1 0 0 5a2.5 2.5 0 0 0 0-5M2 8a6 6 0 1 1 12.001 0A6 6 0 0 1 2 8m6-5a5 5 0 1 0 0 10.001A5 5 0 0 0 8 3");
}

</style>
