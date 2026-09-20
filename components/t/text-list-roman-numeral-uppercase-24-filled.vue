<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d3p26pgvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-list-roman-numeral-uppercase-24-filled" /></template>
<style>
.d3p26pgvf {
  fill: currentColor;
  d: path("M6 2.75a.75.75 0 0 0-1.5 0v4.5a.75.75 0 0 0 1.5 0zM10 5a1 1 0 0 0 0 2h9a1 1 0 1 0 0-2zm0 6.5a1 1 0 1 0 0 2h9a1 1 0 1 0 0-2zm0 6.5a1 1 0 1 0 0 2h9a1 1 0 1 0 0-2zM5.25 9a.75.75 0 0 1 .75.75v4.5a.75.75 0 0 1-1.5 0v-4.5A.75.75 0 0 1 5.25 9M6 16.75a.75.75 0 0 0-1.5 0v4.5a.75.75 0 0 0 1.5 0z");
}

</style>
