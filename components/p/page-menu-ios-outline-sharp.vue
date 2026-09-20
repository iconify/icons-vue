<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hh63sxbfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:page-menu-ios-outline-sharp" /></template>
<style>
.hh63sxbfj {
  fill: currentColor;
  d: path("M3 21v-2h12v2zm0-4v-2h18v2zm0-4V3h18v10zm2-2h14V5H5zm0 0V5z");
}

</style>
