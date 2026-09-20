<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="qyx606bdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:notepad-fill" /></template>
<style>
.qyx606bdm {
  fill: currentColor;
  d: path("M208 32h-24v-8a8 8 0 0 0-16 0v8h-32v-8a8 8 0 0 0-16 0v8H88v-8a8 8 0 0 0-16 0v8H48a8 8 0 0 0-8 8v160a32 32 0 0 0 32 32h112a32 32 0 0 0 32-32V40a8 8 0 0 0-8-8m-88 24a8 8 0 0 1 16 0v8a8 8 0 0 1-16 0ZM80 72a8 8 0 0 1-8-8v-8a8 8 0 0 1 16 0v8a8 8 0 0 1-8 8m80 96H96a8 8 0 0 1 0-16h64a8 8 0 0 1 0 16m0-32H96a8 8 0 0 1 0-16h64a8 8 0 0 1 0 16m24-72a8 8 0 0 1-16 0v-8a8 8 0 0 1 16 0Z");
}

</style>
