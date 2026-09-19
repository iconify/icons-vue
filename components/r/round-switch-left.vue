<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wimfkjt7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-switch-left" /></template>
<style>
.wimfkjt7l {
  fill: currentColor;
  d: path("M8.5 8.62v6.76L5.12 12zm-4.79 2.67a.996.996 0 0 0 0 1.41l4.59 4.59c.62.63 1.7.19 1.7-.7V7.41c0-.89-1.08-1.34-1.71-.71zM14 7.41v9.17c0 .89 1.08 1.34 1.71.71l4.59-4.59a.996.996 0 0 0 0-1.41L15.71 6.7c-.63-.62-1.71-.18-1.71.71");
}

</style>
