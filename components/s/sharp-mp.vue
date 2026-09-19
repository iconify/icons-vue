<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mx5hnabqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-mp" /></template>
<style>
.mx5hnabqm {
  fill: currentColor;
  d: path("M21 3H3v18h18zM6 9h6.5v6H11v-4.5h-1v3H8.5v-3h-1V15H6zm9 6h-1.5V9H18v4.5h-3zm0-3h1.5v-1.5H15z");
}

</style>
