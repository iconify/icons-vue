<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jmpgebk1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:prohibited-48-filled" /></template>
<style>
.jmpgebk1w {
  fill: currentColor;
  d: path("M34.914 10.965c-6.68-5.605-16.653-5.267-22.935 1.014c-6.281 6.282-6.62 16.256-1.014 22.935zm2.121 2.121l-23.949 23.95c6.68 5.605 16.653 5.266 22.935-1.015c6.281-6.282 6.62-16.256 1.014-22.935M9.858 9.858c7.81-7.81 20.474-7.81 28.284 0s7.81 20.474 0 28.284s-20.474 7.81-28.284 0s-7.81-20.474 0-28.284");
}

</style>
