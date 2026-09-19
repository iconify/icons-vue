<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="an00qqb8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-filter-9-plus" /></template>
<style>
.an00qqb8z {
  fill: currentColor;
  d: path("M3 5H1v18h18v-2H3zm11 9V6H9v5h3v1H9v2zm-3-5V8h1v1zm12-8H5v18h18zm-2 8h-2V7h-2v2h-2v2h2v2h2v-2h2v6H7V3h14z");
}

</style>
