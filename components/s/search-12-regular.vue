<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="f0yl5fbho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:search-12-regular" /></template>
<style>
.f0yl5fbho {
  fill: currentColor;
  d: path("M5 1a4 4 0 1 0 2.452 7.16l2.694 2.693a.5.5 0 1 0 .707-.707L8.16 7.453A4 4 0 0 0 5 1M2 5a3 3 0 1 1 6 0a3 3 0 0 1-6 0");
}

</style>
