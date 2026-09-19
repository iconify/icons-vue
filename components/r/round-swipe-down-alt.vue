<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="crcyn-b7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-swipe-down-alt" /></template>
<style>
.crcyn-b7r {
  fill: currentColor;
  d: path("M13 13.9a5 5 0 1 0-2 0v4.27l-.88-.88a.996.996 0 1 0-1.41 1.41l2.59 2.59c.39.39 1.02.39 1.41 0l2.59-2.59a.996.996 0 1 0-1.41-1.41l-.89.88z");
}

</style>
