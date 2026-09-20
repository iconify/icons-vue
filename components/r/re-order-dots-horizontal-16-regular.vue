<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sz4jefb0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:re-order-dots-horizontal-16-regular" /></template>
<style>
.sz4jefb0k {
  fill: currentColor;
  d: path("M11 6a1 1 0 1 0 2 0a1 1 0 0 0-2 0m0 4a1 1 0 1 0 2 0a1 1 0 0 0-2 0m-3 1a1 1 0 1 1 0-2a1 1 0 0 1 0 2M7 6a1 1 0 1 0 2 0a1 1 0 0 0-2 0m-3 5a1 1 0 1 1 0-2a1 1 0 0 1 0 2M3 6a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

</style>
