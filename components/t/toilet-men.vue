<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k_o9d3bnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:toilet-men" /></template>
<style>
.k_o9d3bnt {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.121 2.379Q13.243 1.5 12 1.5q-3 0-3 3t3 3t3-3q0-1.243-.879-2.121M12.875 8.75q3.375 0 3.375 3.375v1.75q0 2.43-1.75 3.111V21.5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T13 21.5v-4.251l-.125.001h-1.75L11 17.249V21.5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T9.5 21.5v-4.514q-1.75-.681-1.75-3.111v-1.75q0-3.375 3.375-3.375z");
}

</style>
