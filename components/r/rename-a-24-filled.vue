<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w8a6grbai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:rename-a-24-filled" /></template>
<style>
.w8a6grbai {
  fill: currentColor;
  d: path("M17.75 2a.75.75 0 1 1 0 1.5H16v17h1.75a.75.75 0 1 1 0 1.5h-5a.75.75 0 0 1 0-1.5h1.75v-17h-1.75a.75.75 0 0 1 0-1.5zM8.914 12H7.086L8 10.031zm4.586 7H5.25A3.25 3.25 0 0 1 2 15.75v-7.5A3.25 3.25 0 0 1 5.25 5h8.25zM8 7.5a.75.75 0 0 0-.68.435l-3.25 7a.75.75 0 0 0 1.36.63l.96-2.065h3.22l.96 2.065a.75.75 0 0 0 1.36-.63l-3.25-7A.75.75 0 0 0 8 7.5M18.75 5A3.25 3.25 0 0 1 22 8.25v7.5A3.25 3.25 0 0 1 18.75 19H17V5z");
}

</style>
