<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qkh3lvd5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:slash-forward-16-filled" /></template>
<style>
.qkh3lvd5y {
  fill: currentColor;
  d: path("M10.267 2.05a.75.75 0 0 1 .434.967l-4 10.5a.75.75 0 0 1-1.402-.534l4-10.5a.75.75 0 0 1 .968-.434");
}

</style>
