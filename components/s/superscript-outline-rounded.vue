<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uyhxxui5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:superscript-outline-rounded" /></template>
<style>
.uyhxxui5n {
  fill: currentColor;
  d: path("M19.192 9q-.343 0-.575-.232t-.233-.576v-.769q0-.343.233-.575q.232-.232.575-.232H21v-.847h-2.23q-.155 0-.27-.111t-.115-.273t.115-.273t.27-.112h2.192q.343 0 .575.232t.232.576v.769q0 .343-.232.576t-.575.232h-1.808v.846h2.23q.155 0 .27.111q.115.112.115.273t-.115.274q-.115.111-.27.111zM8.008 19q-.328 0-.48-.277q-.153-.277.024-.563l3.64-5.627L7.896 7.45q-.177-.28-.024-.558q.152-.276.469-.276q.146 0 .263.066q.116.067.187.19l3.178 4.936h.023l3.231-4.956q.069-.113.19-.175q.12-.061.255-.061q.332 0 .479.276q.147.277-.03.564l-3.354 5.077l3.685 5.627q.177.286.02.563q-.156.277-.47.277q-.142 0-.26-.067t-.19-.189l-3.556-5.457h-.023l-3.517 5.457q-.069.122-.19.189q-.12.067-.254.067");
}

</style>
