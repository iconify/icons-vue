<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lhar-tiyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-position-square-left-16-filled" /></template>
<style>
.lhar-tiyx {
  fill: currentColor;
  d: path("M2.5 1.75a.75.75 0 0 0 0 1.5h11a.75.75 0 0 0 0-1.5zm7.5 2.5a.75.75 0 0 0 0 1.5h3.5a.75.75 0 0 0 0-1.5zM9.25 7.5a.75.75 0 0 1 .75-.75h3.5a.75.75 0 0 1 0 1.5H10a.75.75 0 0 1-.75-.75M10 9.25a.75.75 0 0 0 0 1.5h3.5a.75.75 0 0 0 0-1.5zM1.75 12.5a.75.75 0 0 1 .75-.75h11a.75.75 0 0 1 0 1.5h-11a.75.75 0 0 1-.75-.75M3.25 7a1.75 1.75 0 1 1 3.5 0v3.5a.75.75 0 0 0 1.5 0V7a3.25 3.25 0 1 0-6.5 0v3.5a.75.75 0 0 0 1.5 0z");
}

</style>
