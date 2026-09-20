<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jl7r83b_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:panel-left-header-20-filled" /></template>
<style>
.jl7r83b_r {
  fill: currentColor;
  d: path("M5 3a3 3 0 0 0-3 3v7a3 3 0 0 0 3 3h10a3 3 0 0 0 3-3V6a3 3 0 0 0-3-3zm12 3v1H8.5V4H15a2 2 0 0 1 2 2m-2 9H8.5V8H17v5a2 2 0 0 1-2 2");
}

</style>
