<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m58ze6b8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:tune-outline-sharp" /></template>
<style>
.m58ze6b8m {
  fill: currentColor;
  d: path("M11 21v-6h2v2h8v2h-8v2zm-8-2v-2h6v2zm4-4v-2H3v-2h4V9h2v6zm4-2v-2h10v2zm4-4V3h2v2h4v2h-4v2zM3 7V5h10v2z");
}

</style>
