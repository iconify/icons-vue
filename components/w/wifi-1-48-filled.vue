<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="npeotj56g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:wifi-1-48-filled" /></template>
<style>
.npeotj56g {
  fill: currentColor;
  d: path("M24 33a3 3 0 1 1 0 6a3 3 0 0 1 0-6m.002-7c4.091 0 7.62 2.397 9.263 5.856a1.5 1.5 0 0 1-2.71 1.288a7.252 7.252 0 0 0-13.106 0a1.5 1.5 0 1 1-2.71-1.288A10.25 10.25 0 0 1 24.002 26M24 18c5.982 0 11.253 3.047 14.345 7.666q.228.34.44.692a1.501 1.501 0 0 1-2.57 1.55a14 14 0 0 0-.363-.574C33.292 23.511 28.939 21 24 21c-4.94 0-9.293 2.511-11.851 6.334q-.189.283-.364.573a1.5 1.5 0 0 1-2.57-1.549q.212-.351.44-.692C12.747 21.046 18.018 18 24 18m0-8c8.358 0 15.728 4.23 20.086 10.658a1.5 1.5 0 1 1-2.483 1.684C37.779 16.702 31.32 13 24 13s-13.779 3.701-17.603 9.342a1.5 1.5 0 0 1-2.482-1.684C8.273 14.23 15.642 10 24 10");
}

</style>
