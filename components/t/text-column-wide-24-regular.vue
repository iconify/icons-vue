<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n7fn2sb4t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-column-wide-24-regular" /></template>
<style>
.n7fn2sb4t {
  fill: currentColor;
  d: path("M3.75 5a.75.75 0 0 0 0 1.5h16.5a.75.75 0 0 0 0-1.5zm0 4a.75.75 0 0 0 0 1.5h16.5a.75.75 0 0 0 0-1.5zM3 13.75a.75.75 0 0 1 .75-.75h16.5a.75.75 0 0 1 0 1.5H3.75a.75.75 0 0 1-.75-.75M3.75 17a.75.75 0 0 0 0 1.5h16.5a.75.75 0 0 0 0-1.5z");
}

</style>
