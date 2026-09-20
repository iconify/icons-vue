<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r9uvx5b4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-stack-below-24-filled" /></template>
<style>
.r9uvx5b4g {
  fill: currentColor;
  d: path("M9.5 9.5v5h5v-5zM8 9.5v5H3.75a.75.75 0 0 1-.75-.75V9.5zM9.5 8h5V3h-5zM16 9.5v5h4.25a.75.75 0 0 0 .75-.75V9.5zM21 8h-5V3h1.75A3.25 3.25 0 0 1 21 6.25zM8 8H3V6.25A3.25 3.25 0 0 1 6.25 3H8zM3.75 19.5a.75.75 0 0 0 0 1.5h16.5a.75.75 0 0 0 0-1.5z");
}

</style>
