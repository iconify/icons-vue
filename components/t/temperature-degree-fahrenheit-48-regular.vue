<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zxpx90bbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:temperature-degree-fahrenheit-48-regular" /></template>
<style>
.zxpx90bbt {
  fill: currentColor;
  d: path("M7.5 14.5a4 4 0 1 1 8 0a4 4 0 0 1-8 0m4-6.5a6.5 6.5 0 1 0 0 13a6.5 6.5 0 0 0 0-13m12.75 0C23.56 8 23 8.56 23 9.25v29.5a1.25 1.25 0 1 0 2.5 0V25h13.25a1.25 1.25 0 1 0 0-2.5H25.5v-12h15.25a1.25 1.25 0 1 0 0-2.5z");
}

</style>
