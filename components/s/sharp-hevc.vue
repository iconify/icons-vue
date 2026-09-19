<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cc07nz52w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-hevc" /></template>
<style>
.cc07nz52w {
  fill: currentColor;
  d: path("M5.5 11h-1V9H3v6h1.5v-2.5h1V15H7V9H5.5zM21 11V9h-4v6h4v-2h-1.5v.5h-1v-3h1v.5zm-6.75 2.5L13.5 9H12l1 6h2.5l1-6H15zM8 9v6h3.5v-1.5h-2v-1h2V11h-2v-.5h2V9z");
}

</style>
