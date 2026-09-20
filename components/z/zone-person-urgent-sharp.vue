<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m899sobas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:zone-person-urgent-sharp" /></template>
<style>
.m899sobas {
  fill: currentColor;
  d: path("M3 6V2h4v1H4v3zm4 14H3v-4h1v3h3zM20 6V3h-3V2h4v4zm-7.701 1.701q-.491-.491-.491-1.201t.491-1.201t1.201-.491t1.201.491t.491 1.201t-.491 1.201q-.492.491-1.201.491t-1.201-.491m-2.883 8.684l1.038-5.331L7.5 12.273V15.5h-1v-3.892l3.989-1.662q.644-.26.95-.353T12 9.5q.39 0 .725.208t.552.561l1 1.6q.237.368.523.71t.654.625l-.525.852q-.464-.371-.89-.853t-.789-1.068l-.835 4.25zM13.736 21l4.899-8.525L23.514 21zm5.153-.727Q19 20.162 19 20t-.111-.273t-.273-.111t-.274.111t-.111.273t.111.273t.274.112q.161 0 .273-.112m-.658-1.889H19v-3.768h-.77z");
}

</style>
