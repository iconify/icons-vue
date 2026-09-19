<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f1zohhbpe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-arrow-downward" /></template>
<style>
.f1zohhbpe {
  fill: currentColor;
  d: path("M11 5v11.17l-4.88-4.88c-.39-.39-1.03-.39-1.42 0a.996.996 0 0 0 0 1.41l6.59 6.59c.39.39 1.02.39 1.41 0l6.59-6.59a.996.996 0 1 0-1.41-1.41L13 16.17V5c0-.55-.45-1-1-1s-1 .45-1 1");
}

</style>
