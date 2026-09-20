<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="j2ju9t22o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:search-square-16-filled" /></template>
<style>
.j2ju9t22o {
  fill: currentColor;
  d: path("M2 4.5A2.5 2.5 0 0 1 4.5 2h7A2.5 2.5 0 0 1 14 4.5v7a2.5 2.5 0 0 1-2.5 2.5h-7A2.5 2.5 0 0 1 2 11.5zM5 7a2 2 0 1 1 4 0a2 2 0 0 1-4 0m2-3a3 3 0 1 0 1.738 5.445l2.408 2.409a.5.5 0 0 0 .708-.708L9.445 8.738A3 3 0 0 0 7 4");
}

</style>
