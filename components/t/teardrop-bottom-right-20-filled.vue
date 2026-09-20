<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="a8z8ucc3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:teardrop-bottom-right-20-filled" /></template>
<style>
.a8z8ucc3v {
  fill: currentColor;
  d: path("M2 10a8 8 0 1 1 16 0v6a2 2 0 0 1-2 2h-6a8 8 0 0 1-8-8");
}

</style>
