<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pnw_h264k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:options-48-regular" /></template>
<style>
.pnw_h264k {
  fill: currentColor;
  d: path("M17.75 29.5a6.25 6.25 0 0 1 6.125 5H42.75a1.25 1.25 0 1 1 0 2.5H23.875a6.252 6.252 0 0 1-12.25 0H5.25a1.25 1.25 0 1 1 0-2.5h6.375c.58-2.853 3.101-5 6.125-5m0 2.5a3.75 3.75 0 1 0 0 7.5a3.75 3.75 0 0 0 0-7.5m12.5-26a6.25 6.25 0 0 1 6.125 5h6.375a1.25 1.25 0 1 1 0 2.5h-6.375a6.252 6.252 0 0 1-12.25 0H5.25a1.25 1.25 0 1 1 0-2.5h18.875c.58-2.853 3.101-5 6.125-5m0 2.5a3.75 3.75 0 1 0 0 7.5a3.75 3.75 0 0 0 0-7.5");
}

</style>
