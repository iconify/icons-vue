<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="by6c_1b_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:split-horizontal-48-regular" /></template>
<style>
.by6c_1b_f {
  fill: currentColor;
  d: path("M42.75 25.5a1.25 1.25 0 1 0 0-2.5H5.25a1.25 1.25 0 1 0 0 2.5zM10.5 39.75V27.5H8v12.25A4.25 4.25 0 0 0 12.25 44h23.5A4.25 4.25 0 0 0 40 39.75V27.5h-2.5v12.25a1.75 1.75 0 0 1-1.75 1.75h-23.5a1.75 1.75 0 0 1-1.75-1.75M40 21V8.25A4.25 4.25 0 0 0 35.75 4h-23.5A4.25 4.25 0 0 0 8 8.25V21h2.5V8.25c0-.966.784-1.75 1.75-1.75h23.5c.967 0 1.75.784 1.75 1.75V21z");
}

</style>
