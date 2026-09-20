<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xdt1b0bcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:network-ping-outline" /></template>
<style>
.xdt1b0bcx {
  fill: currentColor;
  d: path("M4 18v-2h6.5L2 7.5l1.4-1.4l8.6 8.575l5.2-5.2q-.1-.225-.15-.462T17 8.5q0-1.05.725-1.775T19.5 6t1.775.725T22 8.5t-.725 1.775T19.5 11q-.225 0-.437-.037t-.413-.113L13.5 16H20v2z");
}

</style>
