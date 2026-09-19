<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tqb3xcc4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-format-italic" /></template>
<style>
.tqb3xcc4m {
  fill: currentColor;
  d: path("M10 4v3h2.21l-3.42 8H6v3h8v-3h-2.21l3.42-8H18V4z");
}

</style>
