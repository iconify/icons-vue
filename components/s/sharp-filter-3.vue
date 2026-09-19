<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f_ixx4bje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-filter-3" /></template>
<style>
.f_ixx4bje {
  fill: currentColor;
  d: path("M23 1H5v18h18zm-2 16H7V3h14zM3 5H1v18h18v-2H3zm14 10V5h-6v2h4v2h-2v2h2v2h-4v2z");
}

</style>
