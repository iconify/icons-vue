<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dgi896b-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-filter-1" /></template>
<style>
.dgi896b-x {
  fill: currentColor;
  d: path("M3 5H1v16c0 1.1.9 2 2 2h16v-2H3zm11 10h2V5h-4v2h2zm7-14H7c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V3c0-1.1-.9-2-2-2m0 16H7V3h14z");
}

</style>
