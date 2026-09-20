<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="isq-yrb8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:oval-32-filled" /></template>
<style>
.isq-yrb8m {
  fill: currentColor;
  d: path("M12 6C6.477 6 2 10.477 2 16s4.477 10 10 10h8c5.523 0 10-4.477 10-10S25.523 6 20 6z");
}

</style>
