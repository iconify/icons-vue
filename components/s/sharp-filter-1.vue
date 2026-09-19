<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pz-w2qb-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-filter-1" /></template>
<style>
.pz-w2qb-x {
  fill: currentColor;
  d: path("M3 5H1v18h18v-2H3zm11 10h2V5h-4v2h2zm9-14H5v18h18zm-2 16H7V3h14z");
}

</style>
