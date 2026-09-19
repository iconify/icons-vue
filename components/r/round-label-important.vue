<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rg2uqab7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-label-important" /></template>
<style>
.rg2uqab7u {
  fill: currentColor;
  d: path("M5.94 18.99H15c.65 0 1.26-.31 1.63-.84l3.95-5.57a.99.99 0 0 0 0-1.16l-3.96-5.58A1.95 1.95 0 0 0 15 5H5.94c-.81 0-1.28.93-.81 1.59L9 12l-3.87 5.41c-.47.66 0 1.58.81 1.58");
}

</style>
