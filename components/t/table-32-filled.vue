<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f0mrsjn6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-32-filled" /></template>
<style>
.f0mrsjn6p {
  fill: currentColor;
  d: path("M20 4h-8v6h8zm0 8h-8v8h8zm2 8v-8h6v8zm-2 2h-8v6h8zm2 6v-6h6v1a5 5 0 0 1-5 5zm0-18V4h1a5 5 0 0 1 5 5v1zM9 4h1v6H4V9a5 5 0 0 1 5-5m-5 8h6v8H4zm0 10h6v6H9a5 5 0 0 1-5-5z");
}

</style>
