<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ohbhd7b8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:subscript-outline-rounded" /></template>
<style>
.ohbhd7b8d {
  fill: currentColor;
  d: path("M19.192 19q-.343 0-.575-.232t-.233-.576v-.769q0-.343.233-.575q.232-.233.575-.233H21v-.846h-2.23q-.155 0-.27-.111t-.115-.273t.115-.273t.27-.112h2.192q.343 0 .575.232t.232.576v.769q0 .343-.232.576t-.575.232h-1.808v.846h2.23q.155 0 .27.111q.115.112.115.274q0 .161-.115.273q-.115.111-.27.111zM8.008 17.384q-.328 0-.48-.276q-.153-.277.024-.564l3.64-5.627l-3.296-5.083q-.177-.28-.024-.557Q8.024 5 8.34 5q.146 0 .263.067q.116.067.187.189l3.178 4.936h.023l3.231-4.955q.069-.113.19-.175q.12-.062.255-.062q.332 0 .479.277t-.03.564l-3.354 5.076l3.685 5.627q.177.287.02.564q-.156.277-.47.277q-.142 0-.26-.067t-.19-.19l-3.556-5.457h-.023L8.452 17.13q-.069.122-.19.189q-.12.067-.254.067");
}

</style>
