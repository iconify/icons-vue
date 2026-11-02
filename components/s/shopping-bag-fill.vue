<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m1gj11wiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shopping-bag-fill" /></template>
<style>
.m1gj11wiv {
  fill: currentColor;
  d: path("M8.126 5a4 4 0 0 1 7.748 0H17a3 3 0 0 1 3 3v11a3 3 0 0 1-3 3H7a3 3 0 0 1-3-3V8a3 3 0 0 1 3-3Zm2.141 0h3.466a2 2 0 0 0-3.466 0");
}

</style>
