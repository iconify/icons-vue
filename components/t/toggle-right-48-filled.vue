<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ng6vk_b1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:toggle-right-48-filled" /></template>
<style>
.ng6vk_b1x {
  fill: currentColor;
  d: path("M44 24c0-5.523-4.477-10-10-10H14C8.477 14 4 18.477 4 24s4.477 10 10 10h20c5.523 0 10-4.477 10-10m-5.5 0a5 5 0 1 1-10 0a5 5 0 0 1 10 0");
}

</style>
