<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ncxxrcc3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:person-prohibited-20-filled" /></template>
<style>
.ncxxrcc3g {
  fill: currentColor;
  d: path("M9 2a4 4 0 1 0 0 8a4 4 0 0 0 0-8m-4.991 9A2 2 0 0 0 2 13c0 1.691.833 2.966 2.135 3.797C5.417 17.614 7.145 18 9 18q.617 0 1.21-.057A5.48 5.48 0 0 1 9 14.5c0-1.33.472-2.55 1.257-3.5zM10 14.5a4.5 4.5 0 1 0 9 0a4.5 4.5 0 0 0-9 0m2.404 2.803l4.9-4.9a3.5 3.5 0 0 1-4.9 4.9m-.707-.707a3.5 3.5 0 0 1 4.9-4.9z");
}

</style>
