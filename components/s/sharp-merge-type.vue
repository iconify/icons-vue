<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lebgayb6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-merge-type" /></template>
<style>
.lebgayb6s {
  fill: currentColor;
  d: path("M17 20.41L18.41 19L15 15.59L13.59 17zM7.5 8H11v5.59L5.59 19L7 20.41l6-6V8h3.5L12 3.5z");
}

</style>
