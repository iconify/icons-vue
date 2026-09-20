<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="b47wqyb9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:wifi-high-thin" /></template>
<style>
.b47wqyb9o {
  fill: currentColor;
  d: path("M136 204a8 8 0 1 1-8-8a8 8 0 0 1 8 8m98.54-113.9a168 168 0 0 0-213.08 0a4 4 0 1 0 5.08 6.18a160 160 0 0 1 202.92 0a4 4 0 0 0 5.08-6.18m-32.06 35.81a120 120 0 0 0-149 0a4 4 0 0 0 5 6.27a112 112 0 0 1 139 0a4 4 0 0 0 5-6.27m-32.13 35.86a72 72 0 0 0-84.7 0a4 4 0 1 0 4.7 6.46a64.07 64.07 0 0 1 75.3 0a4 4 0 0 0 5.58-.87a4 4 0 0 0-.88-5.59");
}

</style>
