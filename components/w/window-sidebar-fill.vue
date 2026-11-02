<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w_2jjd36c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:window-sidebar-fill" /></template>
<style>
.w_2jjd36c {
  fill: currentColor;
  d: path("M22 18a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3Zm-3 1a1 1 0 0 0 1-1V9H10v10Z");
}

</style>
